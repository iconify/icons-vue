<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zn00nmbrt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:arrow-swap-sharp" /></template>
<style>
.zn00nmbrt {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M18 21V10C18 8.3431 16.657 7 15 7C13.343 7 12 8.3431 12 10V14C12 15.6569 10.657 17 9 17C7.343 17 6 15.6569 6 14V3M21.293 17.7071L18 21L14.707 17.7071M9.293 6.2929L6 3L2.707 6.2929");
}

</style>
