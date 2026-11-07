<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qafraccrx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:link-horizontal-off-round" /></template>
<style>
.qafraccrx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M8 8H7a4 4 0 1 0 0 8h2m6-8h2a4 4 0 0 1 3.284 6.284M8 12h4M2 2l20 20");
}

</style>
