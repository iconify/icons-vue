<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="klh0dobdz"/><path class="c63z0bddk"/><path class="xhrh_xb0s"/><path class="t4hxo2bao"/><path class="mqtixbwqo"/><path class="yam3-1b2z"/><path class="mei2sobow"/><path class="xmopbdc-t"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:coffee-table-duotone-regular" /></template>
<style>
.c63z0bddk {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M5 8v12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.klh0dobdz {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M2 8h20");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.mei2sobow {
  d: path("M19 8v12");
}

.mqtixbwqo {
  d: path("M2 8h20");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.t4hxo2bao {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M5 15h14");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.xhrh_xb0s {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M19 8v12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.xmopbdc-t {
  d: path("M5 15h14");
}

.yam3-1b2z {
  d: path("M5 8v12");
}

</style>
