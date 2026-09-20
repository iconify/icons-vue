<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="jdlyngb5v"/><path class="f4fg8zbxd"/><path class="pilb5jbne"/><path class="olzfpgbos"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:arrow-up-left-duotone-thin" /></template>
<style>
.f4fg8zbxd {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M4 14V4h10");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jdlyngb5v {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M20 20 4 4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.olzfpgbos {
  d: path("M4 14V4h10");
}

.pilb5jbne {
  d: path("M20 20 4 4");
}

</style>
