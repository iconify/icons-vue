<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p6h1pk2wx.css';
import '../../css/k/kj5yxug5q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p6h1pk2wx"/><path class="kj5yxug5q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:camera-off" /></template>
