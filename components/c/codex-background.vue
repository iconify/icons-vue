<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="d4yhrqtoo"/><path class="trivbdcpl"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:codex-background" /></template>
<style>
.d4yhrqtoo {
  fill: var(--svg-color--161b14, #161b14);
  d: path("M24 0H0v24h24z");
}

.ft5dv1b6b {
  fill: none;
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.trivbdcpl {
  fill: var(--svg-color--f8e6b6, #f8e6b6);
  d: path("M11.82 4c0 2.435-.862 4.279-2.01 5.626a15.9 15.9 0 0 0 4.12-3.666l.879.667a17 17 0 0 1-4.471 3.961c2.064-.492 4.111-1.19 5.427-2.117l.645.888c-1.312.925-3.18 1.605-5.032 2.095h7.481L19 12.528c-1.909.494-5.711 2.684-5.711 7.472H12.18c0-2.435.862-4.279 2.01-5.626a15.9 15.9 0 0 0-4.12 3.666l-.878-.667a17 17 0 0 1 4.47-3.961c-2.064.492-4.111 1.19-5.427 2.117l-.645-.888c1.312-.925 3.18-1.605 5.032-2.095H5.141L5 11.472c1.909-.494 5.711-2.684 5.711-7.472z");
}

</style>
