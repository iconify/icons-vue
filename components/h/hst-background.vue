<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="hlgrvobzk"/><path class="knkb1mb-a"/><path clip-rule="evenodd" class="pint0eb_r"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:hst-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.hlgrvobzk {
  fill: var(--svg-color--545eff, #545eff);
  d: path("M24 0H0v24h24z");
}

.knkb1mb-a {
  fill: var(--svg-color--fff, #fff);
  d: path("M15.952 16C18.188 16 20 14.21 20 12s-1.812-4-4.048-4c-1.958 0-3.592 1.374-3.967 3.2H16a.8.8 0 1 1 0 1.6h-4.015c.375 1.826 2.009 3.2 3.967 3.2");
}

.pint0eb_r {
  fill: var(--svg-color--fff, #fff);
  fill-rule: evenodd;
  d: path("M4.8 8a.8.8 0 0 0-.8.8v6.4a.8.8 0 0 0 .8.8h6.4a.8.8 0 0 0 .8-.8V8.8a.8.8 0 0 0-.8-.8zm7.198 3.2h-3.27L7.2 12.8h4.798z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

</style>
