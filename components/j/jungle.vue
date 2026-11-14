<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p50nfoxuw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:jungle" /></template>
<style>
.p50nfoxuw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10.5 14c-.25-4.5-2.25-9-6-10.75l-1 3.5l3 .75l-3 2.5l3.25.75l-2 2.25c1.5 1 3.75 1.25 5.75 1m3 0c.25-4.5 2.25-9 6-10.75l1 3.5l-3 .75l3 2.5l-3.25.75l2 2.25c-1.5 1-3.75 1.25-5.75 1M12 21.5v-5.25c0-1.25-.75-2-1.5-2.25m1.5 2.25c0-1.25.75-2 1.5-2.25");
}

</style>
