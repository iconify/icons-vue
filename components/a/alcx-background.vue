<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="abxh8tbll"/><path clip-rule="evenodd" class="xz5gmrhvl"/><path class="ak68p1bre"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:alcx-background" /></template>
<style>
.abxh8tbll {
  fill: var(--svg-color--ecbe9d, #ecbe9d);
  d: path("M24 0H0v24h24z");
}

.ak68p1bre {
  fill: var(--svg-color--fff, #fff);
  d: path("M11.808 5.88V4.369h.445v1.51l5.08 4.045v4.031l-.858.712l1.018 1.777h-3.28l-2.178 1.796l-2.249-1.796h-3.12l.933-1.737l-.933-.752V9.92l5.142-4.045zm.222.387l-4.786 3.768l1.982 1.592l2.809-4.747l2.742 4.813l1.982-1.658zm4.858 4.24l-1.884 1.577l1.249 2.196l.635-.534zm-7.315 1.4l2.68 2.155V16h4.475l-4.702-8.236zm2.68 4.537v1.04l1.262-1.04zm-.445 1.05v-3.219L7.11 10.498v3.249zm-3.853-2.508L7.408 16h1.827z");
}

.ft5dv1b6b {
  fill: none;
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.xz5gmrhvl {
  fill: var(--svg-color--fff, #fff);
  fill-rule: evenodd;
  d: path("M12 20a7.999 7.999 0 1 0 0-15.998A7.999 7.999 0 0 0 12 20m0-.445a7.556 7.556 0 1 0 0-15.111a7.556 7.556 0 0 0 0 15.112");
}

</style>
