<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o9rcvufab"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:business-card-scan" /></template>
<style>
.o9rcvufab {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 7V4.5a2 2 0 0 1 2-2H7m10 0h2.5a2 2 0 0 1 2 2V7m0 10v2.5a2 2 0 0 1-2 2H17m-10 0H4.5a2 2 0 0 1-2-2V17m6.125-9h6.75A2.625 2.625 0 0 1 18 10.625v2.75A2.625 2.625 0 0 1 15.375 16h-6.75A2.625 2.625 0 0 1 6 13.375v-2.75A2.625 2.625 0 0 1 8.625 8M4 12h16");
}

</style>
