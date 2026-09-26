<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fhdk_e98b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:cctv-sharp" /></template>
<style>
.fhdk_e98b {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M7.0923 3L17.2913 7.1207L14.6691 13.611L4.47 9.4903L7.0923 3ZM16.5421 8.9751L21.0001 8.6191L18.3778 15.1094L15.4183 11.7566M6.788 10.4269L6.788 17L3 17M3 12L3 22");
}

</style>
