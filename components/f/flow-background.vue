<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="iv8_1hb4z"/><path clip-rule="evenodd" class="kuo26bcdp"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:flow-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.iv8_1hb4z {
  fill: var(--svg-color--00ef8b, #00ef8b);
  d: path("M24 0H0v24h24z");
}

.kuo26bcdp {
  fill: var(--svg-color--000, #000);
  fill-rule: evenodd;
  d: path("M19.638 7.5h-3.6c-.775 0-1.4.785-1.4 1.54v.46h-4v-.46c0-2.78 2.32-5.04 5.185-5.04h3.815zm-9 7.25c0 .785-.465 1.43-1.25 1.43c-1 0-1.43-.645-1.43-1.43s.645-1.25 1.43-1.25h1.25zm4-1.25v1.02c0 2.9-2.35 5.48-5.25 5.48a5.255 5.255 0 0 1 0-10.5h1.25v4zm0 0v-4h4v4z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

</style>
