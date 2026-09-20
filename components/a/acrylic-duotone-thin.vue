<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="hvujbjbzr"/><path class="pccmg_b3k"/><path class="iu91ib-mt"/><path class="e-07m9b9c"/><path class="pw9d8_-zo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:acrylic-duotone-thin" /></template>
<style>
.e-07m9b9c {
  d: path("M6 11h12");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.hvujbjbzr {
  fill: currentColor;
  d: path("M6 20V8h12v12Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.iu91ib-mt {
  d: path("m6 8 3 -3h6l3 3");
}

.pccmg_b3k {
  d: path("M6 20V8h12v12Z");
}

.pw9d8_-zo {
  d: path("M10 5V2h4v3");
}

</style>
