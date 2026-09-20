<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="j7wks1zrv"/><path class="fqbiv0ris"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:go-background" /></template>
<style>
.fqbiv0ris {
  fill: var(--svg-color--fff, #fff);
  d: path("M20 12.05c0-5.868-5.365-8.278-8.185-8.033c-.52 0-1.115.345-1.115.97s.365 1.025 2.085 1.195c1.45.14 2.825 1.234 3.05 1.46c.34.33.385.774.214 1.134a1.1 1.1 0 0 1-1 .61c-.47.015-.624-.065-1.32-.505a3.06 3.06 0 0 0-1.914-.585C9.44 8.371 8 10.191 8 12.056a3.835 3.835 0 0 0 3.815 3.7a3.77 3.77 0 0 0 3.37-2.105c.22-.45-.09-.64-.27-.65h-3.1c-.375 0-1.115-.125-1.115-.95c0-.82.65-1.05 1.02-1.05h5.4c.48.035.65.35.674.53c.02 4.234-2.61 5.5-3.604 5.9c-.83.34-1.68.55-2.585.55c-.5 0-.95.374-.9 1.06A1 1 0 0 0 11.6 20c6.474 0 8.4-5.324 8.4-7.95M8.5 7.001a1 1 0 1 0 0-2a1 1 0 0 0 0 2M6 9.501a1 1 0 1 0 0-2a1 1 0 0 0 0 2m-1 3.5a1 1 0 1 0 .001-2a1 1 0 0 0 0 2M6 16.5a1 1 0 1 0 .001-2a1 1 0 0 0 0 2M8.5 19a1 1 0 1 0 0-2a1 1 0 0 0 0 2");
}

.ft5dv1b6b {
  fill: none;
}

.j7wks1zrv {
  fill: var(--svg-color--008acb, #008acb);
  d: path("M24 0H0v24h24z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

</style>
