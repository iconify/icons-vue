<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dt0cm9dhy.css';
import '../../css/m/m7_yunpth.css';
import '../../css/l/llod8s1is.css';
import '../../css/m/m3y59dfla.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="m7_yunpth"/><path class="llod8s1is wm-a"/><path class="m3y59dfla"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:alert-triangle-duo" /></template>
