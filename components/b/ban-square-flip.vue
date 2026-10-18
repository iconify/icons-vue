<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="smjlvu3lp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:ban-square-flip" /></template>
<style>
.smjlvu3lp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M21 6C21 4.3431 19.6569 3 18 3L6 3C4.3431 3 3 4.3431 3 6L3 18C3 19.6569 4.3431 21 6 21L18 21C19.6569 21 21 19.6569 21 18ZM20.1213 3.8787L3.8787 20.1213");
}

</style>
