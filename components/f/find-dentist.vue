<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="lc3k8q4bt"/><path class="ge5vtt2tz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:find-dentist" /></template>
<style>
.ge5vtt2tz {
  d: path("M10.75 6.75C9.5 6.75 9 7.75 9 9s.75 1.75 1 2.75l.5 1.5l1.5-2l1.5 2l.5-1.5c.25-1 1-1.5 1-2.75s-.5-2.25-1.75-2.25c-.75 0-.75.5-1.25.5s-.5-.5-1.25-.5Z");
}

.lc3k8q4bt {
  d: path("M12 21.5c-4-4-7.5-8-7.5-12a7.5 7.5 0 0 1 15 0c0 4-3.5 8-7.5 12Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
