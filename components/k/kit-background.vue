<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="a7kejnbnz"/><path clip-rule="evenodd" class="isrmpjwbt"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:kit-background" /></template>
<style>
.a7kejnbnz {
  fill: var(--svg-color--6025e1, #6025e1);
  d: path("M24 0H0v24h24z");
}

.ft5dv1b6b {
  fill: none;
}

.isrmpjwbt {
  fill: var(--svg-color--fff, #fff);
  fill-rule: evenodd;
  d: path("M5.882 6.16v11.581L9.742 20l8.376-4.047V7.981L10.132 4zm.146.056l3.619 2.509V19.83l.753-3.892l3.953-1.765v-4.33l-8.325-3.63z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

</style>
