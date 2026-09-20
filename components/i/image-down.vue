<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/t/t6lndlu0r.css';
import '../../css/o/ol5--vb1y.css';
import '../../css/y/ynnirwbpa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="t6lndlu0r"/><path clip-rule="evenodd" class="ol5--vb1y"/><path class="ynnirwbpa"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:image-down" /></template>
