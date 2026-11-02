<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f_cmsnbjk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:cpu-sharp" /></template>
<style>
.f_cmsnbjk {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M6 6h12v12H6Zm4-3v3m0 12v3M3 10h3m12 0h3m-7-7v3m0 12v3M3 14h3m12 0h3m-11-4h4v4h-4Z");
}

</style>
