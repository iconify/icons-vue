<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="sx2lz1bpy"/><path class="lrubhr9hg"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:blz-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.lrubhr9hg {
  fill: var(--svg-color--fff, #fff);
  d: path("M12 6.618A1.31 1.31 0 1 0 12 4a1.31 1.31 0 0 0 0 2.618M12 20a1.309 1.309 0 1 0 0-2.618A1.309 1.309 0 0 0 12 20m.468-12.675h-.936v1.87h.936zm0 7.48h-.936v1.87h.936zM6.618 12A1.309 1.309 0 1 0 4 12a1.309 1.309 0 0 0 2.618 0m12.073-1.31a1.31 1.31 0 1 1 0 2.62a1.31 1.31 0 0 1 0-2.62M7.325 12.468v-.935h1.87v.935zm7.48 0v-.935h1.87v.935zm-6.617-6.12A1.31 1.31 0 1 1 6.336 8.2a1.31 1.31 0 0 1 1.852-1.852m9.465 11.306a1.31 1.31 0 0 0 .283-1.427a1.31 1.31 0 1 0-.284 1.427M9.41 8.065L8.073 9.411l1.236 1.243l1.338-1.345zm5.259 5.259l-1.347 1.346l1.244 1.243l1.338-1.345zm1.137-5.13a1.31 1.31 0 0 0 2.135-.425a1.309 1.309 0 1 0-2.135.424m-7.614 9.454a1.31 1.31 0 0 1-1.851 0a1.31 1.31 0 0 1 0-1.852a1.31 1.31 0 1 1 1.851 1.852m2.331-4.172a2.08 2.08 0 0 0 2.275.452A2.08 2.08 0 0 0 14.087 12a2.087 2.087 0 1 0-3.563 1.476m5.418-4.065l-1.36-1.353l-1.244 1.244l1.36 1.36zm-5.259 5.265l-1.36-1.36L8.08 14.56l1.36 1.353z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.sx2lz1bpy {
  fill: var(--svg-color--275589, #275589);
  d: path("M24 0H0v24h24z");
}

</style>
