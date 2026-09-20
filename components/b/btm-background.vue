<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="ja1r76bmv"/><path class="ubkp13b4i"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:btm-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.ja1r76bmv {
  fill: var(--svg-color--6c5a5a, #6c5a5a);
  d: path("M24 0H0v24h24z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.ubkp13b4i {
  fill: var(--svg-color--fff, #fff);
  d: path("m7.864 11.504l-1.4 2.96l.648 2.424l1.656.44l2.048 2.048L10.2 20l-4.888-1.312L4 13.8l5.256-5.256zl-1.4 2.96l4.352-4.36l-1.56-1.56zm2.24 1.68l4.352 4.352l2.432-.648l.44-1.656l2.048-2.048l.624.616l-1.312 4.888L13.8 20l-5.256-5.256zm3.792-2.368L9.544 6.464l-2.432.648l-.44 1.656l-2.048 2.048L4 10.2l1.312-4.888L10.2 4l5.256 5.256zm1.336-4.144l-2.048-2.048L13.8 4l4.888 1.312L20 10.2l-5.256 5.256l-1.56-1.56l4.352-4.36l-.648-2.424z");
}

</style>
