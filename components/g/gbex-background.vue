<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="kchk01b-e"/><path class="svm5bkl-y"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:gbex-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.kchk01b-e {
  fill: var(--svg-color--fe036a, #fe036a);
  d: path("M24 0H0v24h24z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.svm5bkl-y {
  fill: var(--svg-color--fff, #fff);
  d: path("M6.525 12a3.37 3.37 0 0 0 3.369 3.37h6.737c.282 0 .843-.169.843-.843s-.56-.842-.843-.842h-6.316V11.16h6.106c.282 0 1.053-.169 1.053-.842c0-.843-.632-.843-1.053-.843h-1.474V6.948h2.527c.77 0 2.526.42 2.526 2.737c0 .632-.337 2.232-1.684 2.737c.56.071 1.684.59 1.684 2.105c0 1.895-.842 3.37-3.369 3.37H9.473v-.018a5.896 5.896 0 1 1 4.754-9.878L12.37 9.714a3.37 3.37 0 0 0-5.845 2.287");
}

</style>
