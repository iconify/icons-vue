<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="h72s4782c"/><path class="cx3249bwo"/><path class="va1bnfbxe"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:cosmos-flower" /></template>
<style>
.cx3249bwo {
  fill: currentColor;
  d: path("M12 9.5h.01");
}

.h72s4782c {
  d: path("m17 8.125l.776-.055a.416.416 0 0 1 .349.68a1.17 1.17 0 0 0 0 1.5a.416.416 0 0 1-.349.68L17 10.875a.654.654 0 0 0-.509 1.116l.634.634a.442.442 0 0 1-.25.75a1.18 1.18 0 0 0-1 1a.442.442 0 0 1-.75.25l-.634-.634a.654.654 0 0 0-1.116.509l.055.776a.416.416 0 0 1-.68.349a1.17 1.17 0 0 0-1.5 0a.416.416 0 0 1-.68-.349l.055-.776a.654.654 0 0 0-1.116-.509l-.634.634a.442.442 0 0 1-.75-.25a1.18 1.18 0 0 0-1-1a.442.442 0 0 1-.25-.75l.634-.634A.654.654 0 0 0 7 10.875l-.776.055a.416.416 0 0 1-.349-.68a1.17 1.17 0 0 0 0-1.5a.416.416 0 0 1 .349-.68L7 8.125a.654.654 0 0 0 .509-1.116l-.634-.634a.442.442 0 0 1 .25-.75a1.18 1.18 0 0 0 1-1a.442.442 0 0 1 .75-.25l.634.634a.654.654 0 0 0 1.116-.509l-.055-.776a.416.416 0 0 1 .68-.349a1.17 1.17 0 0 0 1.5 0a.416.416 0 0 1 .68.349l-.055.776a.654.654 0 0 0 1.116.509l.634-.634a.442.442 0 0 1 .75.25a1.18 1.18 0 0 0 1 1a.442.442 0 0 1 .25.75l-.634.634A.654.654 0 0 0 17 8.125M12 15v6.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.va1bnfbxe {
  d: path("M12 20.5c-1.5-1.75-4-2-5.5-1c1.5 1.75 4 2.25 5.5 1");
}

</style>
