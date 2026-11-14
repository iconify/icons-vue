<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="gfs7hzh3s"/><path class="h9_vbjn0l"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:crystal-gem" /></template>
<style>
.gfs7hzh3s {
  d: path("M12 2.5L17 7v10l-5 4.5L7 17V7Z");
}

.h9_vbjn0l {
  d: path("m7 7l5 2l5-2m-5 2v12.5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
