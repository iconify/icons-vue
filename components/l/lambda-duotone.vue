<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gxf-dyb0n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:lambda-duotone" /></template>
<style>
.gxf-dyb0n {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M5 5.5C5 4.1193 6.1193 3 7.5 3C8.6348 3 9.6273 3.7644 9.9171 4.8616L13.222 17.3749C13.9562 20.1546 17.802 20.4095 18.8966 17.7511L19 17.5M11.5383 11L5 21");
}

</style>
