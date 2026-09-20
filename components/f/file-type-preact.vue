<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="phg1nd_pu"/><ellipse transform="rotate(-37.5 16.007 15.996)" class="c11ae2beh"/><ellipse transform="rotate(-52.5 15.998 15.994)" class="kycnyrzku"/><circle class="lowvkw5lw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:file-type-preact" /></template>
<style>
.c11ae2beh {
  cx: 16px;
  cy: 16px;
  fill: none;
  stroke: var(--svg-color--fff, #fff);
  rx: 10.72px;
  ry: 4.1px;
}

.kycnyrzku {
  cx: 16px;
  cy: 16px;
  fill: none;
  stroke: var(--svg-color--fff, #fff);
  rx: 4.1px;
  ry: 10.72px;
}

.lowvkw5lw {
  cx: 16px;
  cy: 16px;
  r: 1.86px;
  fill: var(--svg-color--fff, #fff);
}

.phg1nd_pu {
  fill: var(--svg-color--673ab8, #673ab8);
  d: path("m16 2l12.12 7v14L16 30L3.88 23V9z");
}

</style>
