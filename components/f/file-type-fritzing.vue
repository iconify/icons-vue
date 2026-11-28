<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g transform="translate(1.03 1.03)scale(.93589)"><rect class="rv_hicc7s"/><g transform="translate(.04)" class="dlrjxpbzv"><path class="ck66jbbhb"/><circle class="tz9ka4bhy"/></g></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:file-type-fritzing" /></template>
<style>
.ck66jbbhb {
  stroke-width: var(--svg-stroke-width--2-99px, 2.99px);
  d: path("M20.88 6.04s-1.74-.04-4.6.03c-.9.02-1.97 1.08-2 1.73c-.02.87.05 12.49.05 12.49m-3.28-7.78h7.8");
}

.dlrjxpbzv {
  fill: none;
  stroke: var(--svg-color--fff, #fff);
  stroke-linecap: round;
  stroke-linejoin: round;
}

.rv_hicc7s {
  width: 29.77px;
  height: 29.77px;
  x: 1.11px;
  y: 1.11px;
  fill: var(--svg-color--d33020, #d33020);
  rx: 6.6px;
  ry: 6.6px;
}

.tz9ka4bhy {
  cx: 14.4px;
  cy: 23.77px;
  r: 2.57px;
  stroke-width: var(--svg-stroke-width--2-23px, 2.23px);
}

</style>
