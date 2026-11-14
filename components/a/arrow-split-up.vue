<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="tvql_fb0l"/><path class="a2psuhk-y"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:arrow-split-up" /></template>
<style>
.a2psuhk-y {
  d: path("m4 7l3-3l3 3m4 0l3-3l3 3");
}

.tvql_fb0l {
  d: path("M12 20.5V15c0-3-5-3-5-6.5V4m5 11c0-3 5-3 5-6.5V4");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
