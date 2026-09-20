<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="xuux5nc2h"/><path class="ttmg4ilbt"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:dfi-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.ttmg4ilbt {
  fill: var(--svg-color--fff, #fff);
  d: path("M14.003 17.963V6.036c2.568.767 4 3.15 4 5.964c0 2.813-1.432 5.197-4 5.963M11.998 4v6.743l-1.016-1.016l-.13-2.535l1.06-3.187a8 8 0 0 0-1.964.27l-.513 1.541l-1.453-.728a8 8 0 0 0-1.579 1.197l2.691 1.348l.079 1.543l-1.543-.079l-1.349-2.69a8 8 0 0 0-1.198 1.579l.73 1.452l-1.543.513A8 8 0 0 0 4 11.914l3.19-1.06l2.535.13L10.74 12l-1.015 1.016l-2.536.13L4 12.085a8 8 0 0 0 .27 1.963l1.543.512l-.73 1.453a8 8 0 0 0 1.198 1.579l1.35-2.69l1.542-.08l-.079 1.543l-2.69 1.349a8 8 0 0 0 1.578 1.198l1.453-.73l.513 1.542a8 8 0 0 0 1.963.27l-1.059-3.187l.13-2.535l1.016-1.016V20A8 8 0 0 0 20 12c0-4.418-3.583-8-8.002-8");
}

.xuux5nc2h {
  fill: var(--svg-color--ff00af, #ff00af);
  d: path("M24 0H0v24h24z");
}

</style>
