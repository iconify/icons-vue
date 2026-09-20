<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="b6yeiwb9r"/><path class="ocholrpwc"/><path class="l74l38ssn"/><path class="yomwopjqx"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:lat-background" /></template>
<style>
.b6yeiwb9r {
  fill: var(--svg-color--050505, #050505);
  d: path("M24 0H0v24h24z");
}

.ft5dv1b6b {
  fill: none;
}

.l74l38ssn {
  fill: var(--svg-color--fff, #fff);
  d: path("M8 18v-2h8V8h2v8.424c0 .87-.738 1.576-1.648 1.576z");
}

.ocholrpwc {
  fill: var(--svg-color--fff, #fff);
  d: path("M7.649 6C6.739 6 6 6.705 6 7.576V16h2V8h8V6z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.yomwopjqx {
  fill: var(--svg-color--fff, #fff);
  d: path("M10 10h4v4h-4zm8-6h2v2h-2zM4 18h2v2H4z");
}

</style>
