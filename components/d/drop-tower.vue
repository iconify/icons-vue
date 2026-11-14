<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="dzfc3vbiq"/><path class="bd4teabdo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:drop-tower" /></template>
<style>
.bd4teabdo {
  d: path("M3.5 7H14v3H3.5ZM18 14.5V21m-2.75-2.75L18 21l2.75-2.75");
}

.dzfc3vbiq {
  d: path("M6 21.5v-19h5.5v15.6m0 .3v3.1");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
