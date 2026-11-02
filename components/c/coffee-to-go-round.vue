<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bibsbeu0s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:coffee-to-go-round" /></template>
<style>
.bibsbeu0s {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M6 7c-1 0-1.5-.2-1-1l1-2c.5-1 1-1 2-1h8c1 0 1.5 0 2 1l1 2c.5.8 0 1-1 1Zm0 0l1 12c.1 1.2.8 2 2 2h6c1.2 0 1.9-.8 2-2l1-12M7 12h10M7 16h10");
}

</style>
