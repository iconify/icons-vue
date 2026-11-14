<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="lza-yaczo"/><path class="q7f9sdbem"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:api-auth" /></template>
<style>
.lza-yaczo {
  d: path("m12.201 21.4l-.201.1L3 17V7l9-4.5L21 7v6.438");
}

.q7f9sdbem {
  d: path("m3 7l9 4.5L21 7m-9 4.5v10M7.5 4.75l9 4.5M15 17.5h6v4h-6Zm1.5 0v-1a1.5 1.5 0 0 1 3 0v1");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
