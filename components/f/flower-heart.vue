<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="otr-_krji"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:flower-heart" /></template>
<style>
.otr-_krji {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 13.5c-5.5-3-7.5-6-6.5-8.5c1-2.25 5-2.5 6.5.25c1.5-2.75 5.5-2.5 6.5-.25c1 2.5-1 5.5-6.5 8.5m0 0v8m0-2c-2.5 0-5-1.5-5.5-4c2.5 0 5 1.5 5.5 4m0 0c2.5 0 5-1.5 5.5-4c-2.5 0-5 1.5-5.5 4");
}

</style>
