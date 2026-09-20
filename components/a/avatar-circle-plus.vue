<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/m/m2ly5xbum.css';
import '../../css/e/eoz2-lbpy.css';
import '../../css/s/s5okhf7bz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="m2ly5xbum"/><path class="eoz2-lbpy"/><path class="s5okhf7bz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:avatar-circle-plus" /></template>
