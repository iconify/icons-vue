<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="wty6em6ov"/><path class="qy6tfzh5v"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:ear-infection" /></template>
<style>
.qy6tfzh5v {
  fill: currentColor;
  d: path("M12 7.25v1.5l1.75.25l-1.25 1l.5 1.5l-1.5-.75l-1 1.25v-1.5l-1.75-.25l1.25-1l-.5-1.5l1.5.75Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.wty6em6ov {
  d: path("M6.25 9c0-3.5 2.5-6 6-6c3.25 0 5.5 2.5 5.5 5.75c0 2.75-1.5 4-2.75 5.25s-1.25 2.5-1.75 4.5c-.5 1.75-2 2.5-3.5 2.5c-2 0-3.5-1.5-3.5-3.5");
}

</style>
