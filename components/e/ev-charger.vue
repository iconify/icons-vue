<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ej0ywbbzr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:ev-charger" /></template>
<style>
.ej0ywbbzr {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M5 2L11 2C12.6569 2 14 3.3431 14 5L14 22L2 22L2 5C2 3.3431 3.3431 2 5 2ZM14 22L22 22M14 17L18 17C19.1046 17 20 16.1046 20 15L20 10M18 6L22 6L22 8.5C22 9.3284 21.3284 10 20.5 10L19.5 10C18.6716 10 18 9.3284 18 8.5L18 6ZM22 6L22 4M18 6L18 4M9 8L6 12L10 12L7 16");
}

</style>
