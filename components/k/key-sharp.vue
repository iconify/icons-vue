<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i16a3oyiz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:key-sharp" /></template>
<style>
.i16a3oyiz {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("m12 12l9-9M3 16a5 5 0 1 0 10 0a5 5 0 0 0-10 0m13-8l2 2m1-5l2 2");
}

</style>
