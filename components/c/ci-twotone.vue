<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yv_brepse.css';
import '../../css/s/sl45xjp0u.css';
import '../../css/p/pvujd7blc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="yv_brepse"/><path class="sl45xjp0u"/><path class="pvujd7blc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:ci-twotone" /></template>
