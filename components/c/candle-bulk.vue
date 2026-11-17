<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="srvtewm6y"/><path class="r6b5-8byi"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:candle-bulk" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.r6b5-8byi {
  d: path("M13.224 6.584a6.4 6.4 0 0 1-1.188-1.174q-.165.326-.344.647c-.376.67-.8 1.354-1.346 1.9c-.14.141-.179.528-.179.71c0 .603.297 1.168.793 1.509a1 1 0 0 1-1.134 1.648a3.8 3.8 0 0 1-1.219-1.374c-.478-.91-.592-2.049-.229-3.02c.124-.329.305-.638.554-.887c.402-.403.738-.97 1.015-1.464c.433-.78.806-1.593 1.117-2.43a1 1 0 0 1 1.917.155c.185.928.762 1.67 1.508 2.229q.057.043.108.093c.957.96 1.236 2.228 1.236 3.541a3.8 3.8 0 0 1-.44 1.783a3.8 3.8 0 0 1-1.219 1.374a1 1 0 0 1-1.134-1.648c.496-.342.793-.906.793-1.509c0-.728-.089-1.527-.609-2.083");
}

.srvtewm6y {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M15.564 10.081A2 2 0 0 1 17 12v8a2 2 0 0 1-2 2H9a2 2 0 0 1-2-2v-8c0-.887.586-1.669 1.436-1.919c-.439-1.1-.385-2.657.496-3.538c.402-.403.738-.97 1.015-1.464q.65-1.173 1.117-2.43a1 1 0 0 1 1.917.155c.186.928.762 1.67 1.508 2.229q.057.043.107.093c.958.959 1.237 2.227 1.237 3.541c.002.484-.089.964-.269 1.414");
}

</style>
