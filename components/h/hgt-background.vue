<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="frg9iqqtm"/><path class="vvzuevb6p"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:hgt-background" /></template>
<style>
.frg9iqqtm {
  fill: var(--svg-color--ffc908, #ffc908);
  d: path("M24 0H0v24h24z");
}

.ft5dv1b6b {
  fill: none;
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.vvzuevb6p {
  fill: var(--svg-color--000, #000);
  d: path("M8.5 8.515V4L12 7.292zm0 6.977V20l3.5-3.292zm0-6.992H4l3.286 3.562zm7 0H20l-3.279 3.444zm0 .015V4L12 7.292zm0 6.981V20L12 16.708zm-7 .004H4l3.302-3.43zm7 0H20l-3.298-3.518zM12 14a2 2 0 1 0 0-4a2 2 0 0 0 0 4");
}

</style>
