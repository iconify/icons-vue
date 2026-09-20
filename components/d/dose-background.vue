<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="otfhay6zt"/><path clip-rule="evenodd" class="jr9oy2b1s"/><path class="ofjmm_0dr"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:dose-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.jr9oy2b1s {
  fill: var(--svg-color--fff, #fff);
  fill-rule: evenodd;
  d: path("M11.615 4H6.03A1.555 1.555 0 0 0 4.5 5.58v12.865A1.55 1.55 0 0 0 6.03 20h5.585c4.35 0 7.885-3.61 7.885-8c0-4.415-3.56-8-7.885-8M11.5 17a5 5 0 1 0 0-10a5 5 0 0 0 0 10");
}

.ofjmm_0dr {
  fill: var(--svg-color--fff, #fff);
  d: path("M11.5 14.5c1.39 0 2.5-1.044 2.5-2.36c0-1.31-1.22-2.114-2.16-3a.485.485 0 0 0-.68 0c-.94.886-2.16 1.66-2.16 3c0 1.316 1.135 2.36 2.5 2.36");
}

.otfhay6zt {
  fill: var(--svg-color--131519, #131519);
  d: path("M24 0H0v24h24z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

</style>
