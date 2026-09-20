<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="s0f2y68ic"/><path class="es6v6vufr"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:ava-background" /></template>
<style>
.es6v6vufr {
  fill: var(--svg-color--fff, #fff);
  d: path("M17.546 4H5.58c-.365 0-.445.24-.44.36v3.166c-.005.365.269.48.4.474h4.178v10.663c0 .817.777 1.325 1.251 1.325c.777.006 2.429.023 2.783 0c.36-.028.537-.394.537-.571V8h4.183c.285 0 .377-.286.383-.417c0-.206.01-1.16 0-2.206C18.837 4.337 18.095 4 17.54 4z");
}

.ft5dv1b6b {
  fill: none;
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.s0f2y68ic {
  fill: var(--svg-color--393969, #393969);
  d: path("M24 0H0v24h24z");
}

</style>
