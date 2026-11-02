<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n1_uv1bzy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:cloud-lightning-sharp" /></template>
<style>
.n1_uv1bzy {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M7 15a4 4 0 1 1 0-8c2-6 11-5 11 2a3 3 0 0 1 0 6Zm6 0l-3 3h4l-3 3");
}

</style>
