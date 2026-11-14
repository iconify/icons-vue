<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eq2eroqvw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:funeral-flowers" /></template>
<style>
.eq2eroqvw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 11c-4-1-6.5-4.5-6-8c2.5 1 4.5 2 6 4c1.5-2 3.5-3 6-4c.5 3.5-2 7-6 8m0 0v10.5m0-5.5l-4-2v4Zl4-2v4Z");
}

</style>
