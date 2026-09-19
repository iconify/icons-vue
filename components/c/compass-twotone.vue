<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ceaf9c7tx.css';
import '../../css/w/wzastfpvt.css';
import '../../css/y/yv_brepse.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="ceaf9c7tx"/><path class="wzastfpvt"/><path class="yv_brepse"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:compass-twotone" /></template>
