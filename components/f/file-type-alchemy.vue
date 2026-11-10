<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g transform="translate(-.39 -.39)scale(1.3659)" class="sutwfccoy"><circle class="p058992qq"/><path class="o9i1vmbbc"/><circle class="orel5k_wx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:file-type-alchemy" /></template>
<style>
.o9i1vmbbc {
  d: path("M12 21.13L4.1 7.43h15.8z");
}

.orel5k_wx {
  cx: 12px;
  cy: 12px;
  r: 1.3px;
  fill: var(--svg-color--d8835a, #d8835a);
  stroke: none;
}

.p058992qq {
  cx: 12px;
  cy: 12px;
  r: 9.5px;
}

.sutwfccoy {
  fill: none;
  stroke: var(--svg-color--a3c473, #a3c473);
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
