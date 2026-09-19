<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hntgybcog.css';
import '../../css/m/m4l-9ybuj.css';
import '../../css/g/gnng3obxz.css';
import '../../css/p/pzze8cbzr.css';
import '../../css/u/ue5su15bf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><circle class="m4l-9ybuj"/><path class="gnng3obxz"/><path class="pzze8cbzr"/><path class="ue5su15bf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:loader-pinwheel" /></template>
