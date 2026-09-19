<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/d/d7_y3k80y.css';
import '../../css/m/m471xsbvh.css';
import '../../css/q/qg_-d1bma.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="cuyn6tgcc"><path class="d7_y3k80y"/><path clip-rule="evenodd" class="m471xsbvh"/><path class="qg_-d1bma"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:hot-meal-outline" /></template>
