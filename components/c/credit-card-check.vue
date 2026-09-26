<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jsvbm6bbm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:credit-card-check" /></template>
<style>
.jsvbm6bbm {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M22 9L22 7C22 5.3431 20.6569 4 19 4L5 4C3.3431 4 2 5.3431 2 7L2 17C2 18.6569 3.3431 20 5 20L12 20M2 9L22 9M16 17L18 19L22 15");
}

</style>
