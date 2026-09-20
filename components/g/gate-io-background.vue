<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="wrgfzd9bk"/><path class="c5f1rwbln"/><path class="ea313lb_q"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:gate-io-background" /></template>
<style>
.c5f1rwbln {
  fill: var(--svg-color--fff, #fff);
  d: path("M12 16.4a4.4 4.4 0 0 1 0-8.8V4a8 8 0 1 0 8 8h-3.6a4.4 4.4 0 0 1-4.4 4.4");
}

.ea313lb_q {
  fill: var(--svg-color--17e6a1, #17e6a1);
  d: path("M16.4 7.6H12V12h4.4z");
}

.ft5dv1b6b {
  fill: none;
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.wrgfzd9bk {
  fill: var(--svg-color--2354e6, #2354e6);
  d: path("M24 0H0v24h24z");
}

</style>
