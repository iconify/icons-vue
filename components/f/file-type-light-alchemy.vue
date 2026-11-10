<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g transform="translate(-.39 -.39)scale(1.3659)" class="rh57g4bdk"><circle class="p058992qq"/><path class="o9i1vmbbc"/><circle class="km1pptbay"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:file-type-light-alchemy" /></template>
<style>
.km1pptbay {
  cx: 12px;
  cy: 12px;
  r: 1.3px;
  fill: var(--svg-color--9a4f27, #9a4f27);
  stroke: none;
}

.o9i1vmbbc {
  d: path("M12 21.13L4.1 7.43h15.8z");
}

.p058992qq {
  cx: 12px;
  cy: 12px;
  r: 9.5px;
}

.rh57g4bdk {
  fill: none;
  stroke: var(--svg-color--3f5a2a, #3f5a2a);
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
