<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="j1ufo_j8k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:frame-20-filled" /></template>
<style>
.j1ufo_j8k {
  fill: currentColor;
  d: path("M4.5 2a.5.5 0 0 1 .5.5V4h10V2.5a.5.5 0 0 1 1 0V4h1.5a.5.5 0 0 1 0 1H16v10h1.5a.5.5 0 0 1 0 1H16v1.5a.5.5 0 0 1-1 0V16H5v1.5a.5.5 0 0 1-1 0V16H2.5a.5.5 0 0 1 0-1H4V5H2.5a.5.5 0 0 1 0-1H4V2.5a.5.5 0 0 1 .5-.5");
}

</style>
