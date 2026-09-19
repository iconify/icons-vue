<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/n/n87g3vegy.css';
import '../../css/p/pc4l4cwbu.css';
import '../../css/p/p1i5yb1dj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="n87g3vegy"/><path clip-rule="evenodd" class="pc4l4cwbu"/><path class="p1i5yb1dj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:happy-outline" /></template>
