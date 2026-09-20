<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="bk6onobbj"/><path class="g0gd-ngpb"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:gt-background" /></template>
<style>
.bk6onobbj {
  fill: var(--svg-color--d35756, #d35756);
  d: path("M24 0H0v24h24z");
}

.ft5dv1b6b {
  fill: none;
}

.g0gd-ngpb {
  fill: var(--svg-color--fff, #fff);
  d: path("m19.556 8.444l-4.89 2.667v2.667l1.334-.8v1.844l-4.445 2.511l-3.52-2.275a1.81 1.81 0 0 1-.924-1.591V9.129l3.68-2.24c.245-.138.48-.222.764-.222s.605.084.854.222l3.933 2.24l2.409-1.369l-6.133-3.489A2.2 2.2 0 0 0 11.555 4a1.9 1.9 0 0 0-.977.267L4.444 7.764v7.076c0 .662.356 1.267.934 1.6L11.555 20l6.17-3.564a1.88 1.88 0 0 0 .942-1.614v-3.266l.888-.445z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

</style>
