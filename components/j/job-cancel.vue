<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sz2489bsj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:job-cancel" /></template>
<style>
.sz2489bsj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.4 3.5h13.1v13.1m-3.9 3.9H3.5V7.4M12 8h4.5m-9 4h.6m7.8 0h.6m-9 4H12M3.5 3.5l17 17");
}

</style>
