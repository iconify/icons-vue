<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="o_rtubc4a"/><path class="k4bonx5pg"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:hai-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.k4bonx5pg {
  fill: var(--svg-color--fff, #fff);
  d: path("M4 4.571h1.143v6.858h.571V4.57h1.143v6.858h12v-.572H7.43V4.571h1.14v5.143h10.286v-.571H9.143V4.57h1.143V8h3.428V4.57h1.143V8h.572V4.57h1.142V8h.572V4.57h1.143V8h.571V4.57H20v14.857h-1.143V12.57h-.571v6.858h-1.143V12.57h-12v.572H16.57v6.285h-1.14v-5.142H5.143v.571h9.714v4.572h-1.143v-3.43h-3.428v3.43H9.143v-3.43H8.57v3.43H7.43v-3.43h-.572v3.43H5.714v-3.43h-.571v3.43H4z");
}

.o_rtubc4a {
  fill: var(--svg-color--45e2ba, #45e2ba);
  d: path("M24 0H0v24h24z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

</style>
