<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mwn33o7jc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:cold-pack" /></template>
<style>
.mwn33o7jc {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.5 3h15a1 1 0 0 1 1 1v16a1 1 0 0 1-1 1h-15a1 1 0 0 1-1-1V4a1 1 0 0 1 1-1Zm-1 4h17M12 10v9m-3.75-6.75l7.5 4.5m-7.5 0l7.5-4.5");
}

</style>
