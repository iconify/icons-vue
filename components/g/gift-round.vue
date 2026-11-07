<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k1e164bcp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:gift-round" /></template>
<style>
.k1e164bcp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3 9a2 2 0 0 1 2-2h14a2 2 0 1 1 0 4H5a2 2 0 0 1-2-2m2 2v6a4 4 0 0 0 4 4h6a4 4 0 0 0 4-4v-6m-7-4H9C7 7 6 6 6 5c0-2 2-2 3-1zm0 0h3c2 0 3-1 3-2c0-2-2-2-3-1zm0 0v14");
}

</style>
