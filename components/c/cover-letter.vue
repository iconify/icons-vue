<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="df3b-wgfx"/><path class="w1geybutg"/><path class="jihpo0bnb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:cover-letter" /></template>
<style>
.df3b-wgfx {
  d: path("M9.6 7h3.9v14.5h-11v-7.7");
}

.jihpo0bnb {
  d: path("M16.25 6.75a1.25 1.25 0 1 0 2.5 0a1.25 1.25 0 1 0-2.5 0Zm0 4.25h2.5m-2.5 3h2.5m-13.5 0h5.5m-5.5 3.5H9.5m-5.25-13h2.5V11h-2.5Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.w1geybutg {
  d: path("M9.75 7V4a1.5 1.5 0 0 1 1.5-1.5H20A1.5 1.5 0 0 1 21.5 4v11.5A1.5 1.5 0 0 1 20 17h-6.5");
}

</style>
