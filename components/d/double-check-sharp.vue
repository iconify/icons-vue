<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uxl6s7b2e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:double-check-sharp" /></template>
<style>
.uxl6s7b2e {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M2.2311 10.7118L7.1667 16L16.7964 5.6823M21.7407 10.7191L15.5 18L13.2071 15.7071");
}

</style>
