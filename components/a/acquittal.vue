<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hm_hqdf7d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:acquittal" /></template>
<style>
.hm_hqdf7d {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m10.464 5.172l.708-.708a1.75 1.75 0 0 1 2.474 0l3.89 3.89a1.75 1.75 0 0 1 0 2.474l-.708.708a1.75 1.75 0 0 1-2.474 0l-3.89-3.89a1.75 1.75 0 0 1 0-2.474M12.5 9.5l-8 8m10.25.5l2 2L21 15.75");
}

</style>
