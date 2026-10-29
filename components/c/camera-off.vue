<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dt0cm9dhy.css';
import '../../css/p/psnkz2bcb.css';
import '../../css/y/yd1-_qbdi.css';
import '../../css/k/kajlvyf4t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="psnkz2bcb"/><path class="wm-a yd1-_qbdi"/><path class="kajlvyf4t wm-s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:camera-off" /></template>
