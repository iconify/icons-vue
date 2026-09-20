<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a9b73nb6i.css';
import '../../css/c/c__qdgb1d.css';
import '../../css/k/k-l-zsmjx.css';
import '../../css/i/ij2x_72vy.css';
import '../../css/g/gvgd7ibyf.css';
import '../../css/n/nmjzi7gvr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="a9b73nb6i"/><path class="c__qdgb1d"/><path class="k-l-zsmjx"/><g class="ij2x_72vy"><path class="gvgd7ibyf"/><path class="nmjzi7gvr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:level-slider" /></template>
