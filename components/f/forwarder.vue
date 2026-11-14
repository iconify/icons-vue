<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="en6nizbmm"/><path class="xav8gmb7b"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:forwarder" /></template>
<style>
.en6nizbmm {
  d: path("M2.5 16.5h19v-5l-2-3H17v8");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.xav8gmb7b {
  d: path("M2.5 18.25a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0Zm14.5 0a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0ZM6.5 14.5a2 2 0 1 0 4 0a2 2 0 1 0-4 0Zm4 0a2 2 0 1 0 4 0a2 2 0 1 0-4 0Zm-2-3.5a2 2 0 1 0 4 0a2 2 0 1 0-4 0Zm9-2.5l-3-5l-5.5 2");
}

</style>
