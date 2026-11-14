<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uhecbgbbi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:colour-complementary" /></template>
<style>
.uhecbgbbi {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 9.25a9.5 9.5 0 0 1 6.5-6.5m12 12a9.5 9.5 0 0 1-6.5 6.5M12 2.5a9.5 9.5 0 0 1 9.5 9.5h-4A5.5 5.5 0 0 0 12 6.5Zm0 19A9.5 9.5 0 0 1 2.5 12h4a5.5 5.5 0 0 0 5.5 5.5Z");
}

</style>
