<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qk2ps9bzc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:crypto-gift-card" /></template>
<style>
.qk2ps9bzc {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.25 7h13.5A2.25 2.25 0 0 1 21 9.25a2.25 2.25 0 0 1-2.25 2.25H5.25A2.25 2.25 0 0 1 3 9.25A2.25 2.25 0 0 1 5.25 7m-.75 4.5v7a2 2 0 0 0 2 2h11a2 2 0 0 0 2-2v-7M12 7v13.5M12 7c-2-4-6-3.5-4.5 0M12 7c2-4 6-3.5 4.5 0");
}

</style>
