<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="ifhbbukng"/><path class="agqn2h2nz"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:ipad-background" /></template>
<style>
.agqn2h2nz {
  fill: var(--svg-color--fff, #fff);
  d: path("m4 12l1.263-1.264L6.526 12l-1.263 1.264zm1.684 1.684l1.263-1.263l2.948 2.947l-1.264 1.263zm3.368 0l1.263-1.263l1.264 1.263l-1.264 1.263zM10.737 12l1.264-1.264L13.264 12L12 13.263zm1.684-1.684l1.264-1.263l1.263 1.263l-1.264 1.263zm1.685-1.685l1.263-1.263l2.947 2.948l-1.263 1.263zm-1.685 5.053l1.264-1.263l1.263 1.263l-1.264 1.263zm1.685 1.684l2.947-2.947l1.263 1.263l-2.947 2.947zM17.474 12l1.263-1.264L20 12l-1.263 1.264zm-11.79-1.684l2.947-2.948l1.264 1.263l-2.948 2.948zm3.368 0l1.263-1.263l1.264 1.263l-1.264 1.263z");
}

.ft5dv1b6b {
  fill: none;
}

.ifhbbukng {
  fill: var(--svg-color--f3ba2f, #f3ba2f);
  d: path("M24 0H0v24h24z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

</style>
