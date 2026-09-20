<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="d6gvcvbvs"/><path class="ko10-lu3q"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:la-background" /></template>
<style>
.d6gvcvbvs {
  fill: var(--svg-color--2f355b, #2f355b);
  d: path("M24 0H0v24h24z");
}

.ft5dv1b6b {
  fill: none;
}

.ko10-lu3q {
  fill: var(--svg-color--fff, #fff);
  d: path("m11.822 6.588l-3.838 8.47h2.853l3.872-8.47h3.593L20 17.41h-3.136l-.18-2.353H13.73l-.801 2.353H4L8.85 6.588zm2.479 7.059h2.135l-.387-5.177z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

</style>
