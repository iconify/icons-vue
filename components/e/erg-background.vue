<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="mumfproca"/><path clip-rule="evenodd" class="bsv-sqb4q"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:erg-background" /></template>
<style>
.bsv-sqb4q {
  fill: var(--svg-color--fff, #fff);
  fill-rule: evenodd;
  d: path("m12 4l5.657 2.344L20 12l-2.343 5.657L12 20l-5.656-2.343L4 12l2.344-5.656zm0 .941l4.988 2.07L19.058 12l-2.07 4.988L12 19.058l-4.988-2.07L4.942 12l2.07-4.988zm2.353 3.765H9.647v.941L11.652 12l-2.005 2.353v.941h4.706v-.941H10.95L12.94 12l-1.99-2.353h3.402z");
}

.ft5dv1b6b {
  fill: none;
}

.mumfproca {
  fill: var(--svg-color--000, #000);
  d: path("M24 0H0v24h24z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

</style>
