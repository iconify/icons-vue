<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iv8tc0bwx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:clapper-open" /></template>
<style>
.iv8tc0bwx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 11h16a2 2 0 0 1 2 2v6a2 2 0 0 1-2 2H5a2 2 0 0 1-2-2Zm.543-3.769l13.523-3.623a1.5 1.5 0 0 1 1.837 1.06l.13.483a1.5 1.5 0 0 1-1.061 1.837L4.449 10.612a1.5 1.5 0 0 1-1.837-1.061l-.13-.483a1.5 1.5 0 0 1 1.061-1.837m3.381-.906l2.837 2.863m1.992-4.157l2.838 2.863");
}

</style>
