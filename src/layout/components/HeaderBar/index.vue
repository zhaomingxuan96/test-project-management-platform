<template>
  <div>
    <el-row :gutter="24" style="display: flex; align-items: center;"
    >
      <el-col :span="20" :offset="0"> 
        <!-- 面包屑 -->
        <bread-crumb />
      </el-col>
      <el-col :span="4">
        
        <user-bar />
      </el-col>
    </el-row>
  </div>
</template>

<script setup lang="ts">
import BreadCrumb from './BreadCrumb.vue'
import UserBar from './UserBar.vue'
</script>
<style lang='scss' scoped>
</style>