<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gpmloab-q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="gpmloab-q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:insert-row-right-outlined" /></template>
