<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l345i_b1b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:coupon-sharp" /></template>
<style>
.l345i_b1b {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M21 9V6H3v3a3 3 0 0 1 0 6v3h18v-3a3 3 0 0 1 0-6m-7 1l-4 4M9 9h.01M15 15h.01");
}

</style>
