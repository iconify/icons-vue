<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="rg47f3bdc"/><path class="rb48z6b5c"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:ckp-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.rb48z6b5c {
  fill: var(--svg-color--fff, #fff);
  d: path("m12.075 4l6.748 3.915l-3.077 4.033l2.922 4.226L12.075 20l-6.899-4V8zm.63 13.177a5.16 5.16 0 0 0 3.248-1.144l-.87-1.412a3.7 3.7 0 0 1-2.142.673c-1.948 0-3.53-1.473-3.53-3.294s1.582-3.294 3.53-3.294c.753 0 1.45.221 2.023.593l.848-1.44a5.176 5.176 0 1 0-3.106 9.318");
}

.rg47f3bdc {
  fill: var(--svg-color--1fa4ff, #1fa4ff);
  d: path("M24 0H0v24h24z");
}

</style>
