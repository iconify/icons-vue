<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yv_brepse.css';
import '../../css/z/zbvzoqb3z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="yv_brepse"/><path class="zbvzoqb3z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:exclamation-circle-outline" /></template>
