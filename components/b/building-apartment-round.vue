<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pmyer0w9n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:building-apartment-round" /></template>
<style>
.pmyer0w9n {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3 21h18M7 21V8a4 4 0 0 1 4-4h2a4 4 0 0 1 4 4v13M10 8h.01M14 8h.01M10 12h.01M14 12h.01M10 21v-2a2 2 0 1 1 4 0v2M7 11H5a2 2 0 0 0-2 2v8m14-10h2a2 2 0 0 1 2 2v8");
}

</style>
