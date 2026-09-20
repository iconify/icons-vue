<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="k1eetnbvo"/><path class="da2dpbd0w"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:ichi-background" /></template>
<style>
.da2dpbd0w {
  fill: var(--svg-color--fff, #fff);
  d: path("M19.869 5.835c.235.35.14.82-.21 1.05c-.565.375-1.665.91-3.16 1.32v3.294h.83a.76.76 0 0 1 .77.75a.76.76 0 0 1-.77.75h-.83v2.795c1.5.41 2.6.95 3.16 1.315a.75.75 0 0 1 .21 1.05a.783.783 0 0 1-1.075.21c-.78-.515-3.375-1.675-6.894-1.675s-5.97 1.16-6.674 1.66a.78.78 0 0 1-1.08-.17a.75.75 0 0 1 .175-1.06c.55-.39 1.65-.95 3.18-1.37v-2.755h-.63a.76.76 0 0 1-.77-.75c0-.415.35-.75.77-.75h.63V8.245a10.7 10.7 0 0 1-3.18-1.37a.75.75 0 0 1-.175-1.06a.783.783 0 0 1 1.08-.17a9.9 9.9 0 0 0 3.25 1.28c.974.225 2.13.38 3.424.38c3.52 0 6.114-1.16 6.899-1.675a.78.78 0 0 1 1.07.205m-4.87 9.619v-2.455H9v2.425a17.1 17.1 0 0 1 6 .03m0-3.955V8.55a17.5 17.5 0 0 1-6 .026V11.5z");
}

.ft5dv1b6b {
  fill: none;
}

.k1eetnbvo {
  fill: var(--svg-color--0065e3, #0065e3);
  d: path("M24 0H0v24h24z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

</style>
