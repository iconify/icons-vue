<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yd-xz_bti"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:fiber-splice" /></template>
<style>
.yd-xz_bti {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8 10H4.5a2 2 0 0 0 0 4H8m8-4h3.5a2 2 0 0 1 0 4H16m-5.375-7h2.75A2.625 2.625 0 0 1 16 9.625v4.75A2.625 2.625 0 0 1 13.375 17h-2.75A2.625 2.625 0 0 1 8 14.375v-4.75A2.625 2.625 0 0 1 10.625 7M12 9.5v5");
}

</style>
