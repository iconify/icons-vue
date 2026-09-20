<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="t1l8hactz"/><path class="fwxcxnb4y"/><path class="fzmqv5bvt"/><path class="rp6madc8b"/><path class="jq5p3obdd"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:geeq-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.fwxcxnb4y {
  fill: var(--svg-color--fff, #fff);
  d: path("M12.5 4.5h-1V8h1zm0 11.5h-1v3.5h1z");
}

.fzmqv5bvt {
  fill: var(--svg-color--fff, #fff);
  d: path("M12 20a8 8 0 0 0 6.82-12.185l-.753.692a7 7 0 1 1-.567-.837l.738-.679A7.99 7.99 0 0 0 12 4a8 8 0 0 0-8 8a8 8 0 0 0 8 8");
}

.jq5p3obdd {
  fill: var(--svg-color--fff, #fff);
  d: path("M12 7.5a4.5 4.5 0 0 1 3.653 1.871l-.743.684A3.5 3.5 0 1 0 15.355 13H12.5v-1h3q-.002-.52-.144-.996l.799-.735A4.5 4.5 0 1 1 12 7.5");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.rp6madc8b {
  fill: var(--svg-color--fff, #fff);
  d: path("m17.69 8.855l-.762.701a5.5 5.5 0 1 1-.536-.866l.739-.68a6.49 6.49 0 0 0-5.132-2.51a6.5 6.5 0 1 0 5.69 3.355");
}

.t1l8hactz {
  fill: var(--svg-color--254280, #254280);
  d: path("M24 0H0v24h24z");
}

</style>
