<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/o/oybjd3s2z.css';
import '../../css/t/turgpe-dg.css';
import '../../css/c/ccvr2ibtr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="oybjd3s2z"/><path class="turgpe-dg"/><path class="ccvr2ibtr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:arrows-horizontal" /></template>
