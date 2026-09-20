<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="gtgmjbcgs"/><path clip-rule="evenodd" class="ubh98c8di"/><path class="m6a_x813o"/><path class="pfav5w9ow"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:koge-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.gtgmjbcgs {
  fill: var(--svg-color--ffc800, #ffc800);
  d: path("M24 0H0v24h24z");
}

.m6a_x813o {
  fill: var(--svg-color--fff, #fff);
  d: path("M9.175 8.608v7.61l1.412-.754v-6.07zm2.353 4.696l1.064.81l-1.064.706z");
}

.pfav5w9ow {
  fill: var(--svg-color--fff, #fff);
  d: path("m12.597 11.067l1.167.847l-.951.612l1.195.946l2.226-1.304l-5.84-4.306l-1.219.72l2.353 1.709v1.435z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.ubh98c8di {
  fill: var(--svg-color--fff, #fff);
  fill-rule: evenodd;
  d: path("M12 20a8 8 0 1 0 0-16a8 8 0 0 0 0 16m0-.941a7.06 7.06 0 1 0 0-14.12a7.06 7.06 0 0 0 0 14.12");
}

</style>
