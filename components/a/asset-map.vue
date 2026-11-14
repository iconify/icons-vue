<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="mshnucb-j"/><path class="brtke3vsl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:asset-map" /></template>
<style>
.brtke3vsl {
  d: path("M12 17c-2-2-3-4-3-6.25a3 3 0 0 1 6 0C15 13 14 15 12 17m0-6.25h.01");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.mshnucb-j {
  d: path("m3.361 5.095l2.948-1.388a1.5 1.5 0 0 1 .92-.116l9.542 1.818a1.5 1.5 0 0 0 .92-.116l1.684-.793A1.49 1.49 0 0 1 21.5 5.849v11.699a1.5 1.5 0 0 1-.861 1.357l-2.948 1.388a1.5 1.5 0 0 1-.92.116l-9.542-1.818a1.5 1.5 0 0 0-.92.116l-1.684.793A1.49 1.49 0 0 1 2.5 18.151V6.452a1.5 1.5 0 0 1 .861-1.357M6.75 3.5v15m10.5-13v15");
}

</style>
