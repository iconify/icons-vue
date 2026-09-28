<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="adxo8eaur"><circle class="mho6qfbso"/><circle class="uvo6ztbyb"/><path class="n-od1fk7e"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:file-type-zsh" /></template>
<style>
.adxo8eaur {
  fill: none;
  stroke: var(--svg-color--f15a24, #f15a24);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--2-11px, 2.11px);
}

.mho6qfbso {
  cx: 5.85px;
  cy: 11.9px;
  r: 2.6px;
}

.n-od1fk7e {
  stroke-width: var(--svg-stroke-width--1-35px, 1.35px);
  d: path("M15.2 8.54L2.68 23.46m26.65-.37h-8.95");
}

.uvo6ztbyb {
  cx: 12px;
  cy: 20.1px;
  r: 2.6px;
}

</style>
