<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="dlisdl9nd"/><path class="uq7srpbjg"/><circle class="ed-2fac4b"/><path class="u5u3z8b-h"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:fingerprint-evidence" /></template>
<style>
.dlisdl9nd {
  d: path("M4.25 15.5v-4a5.5 5.5 0 0 1 11 0");
}

.ed-2fac4b {
  cx: 16.25px;
  cy: 16.25px;
  r: 3.25px;
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.u5u3z8b-h {
  d: path("m18.6 18.6l2.65 2.65");
}

.uq7srpbjg {
  d: path("M7.25 17.75V11.5a2.5 2.5 0 0 1 5 0v.5m-2.5-.5V20");
}

</style>
