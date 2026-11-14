<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bpl33cbgw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:audience-custom" /></template>
<style>
.bpl33cbgw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12.172 20.5H4c-.6 0-1-.4-1-1c0-3.25 3.25-5.5 7.5-5.5q.865 0 1.666.121M6.5 7a4 4 0 1 0 8 0a4 4 0 1 0-8 0Zm8.5 8.75h6.5m-6.5 4.5h6.5m-4.5-6v3m2.5 1.5v3");
}

</style>
