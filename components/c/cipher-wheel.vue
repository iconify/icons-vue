<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><circle class="dbgvcxwad"/><path class="ynfffkbqo"/><circle class="do0vcyb9o"/><path class="m1nix48ki"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:cipher-wheel" /></template>
<style>
.dbgvcxwad {
  cx: 12px;
  cy: 12px;
  r: 9.25px;
}

.do0vcyb9o {
  cx: 12px;
  cy: 12px;
  r: 5.25px;
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.m1nix48ki {
  d: path("M12 12V8.75");
}

.ynfffkbqo {
  d: path("m18.66 13.79l.97.25m-2.75 2.84l.71.71m-3.8 1.07l.25.97m-3.83-.97l-.25.97m-2.84-2.75l-.71.71m-1.07-3.8l-.97.25m.97-3.83l-.97-.25m2.75-2.84l-.71-.71m3.8-1.07l-.25-.97m3.83.97l.25-.97m2.84 2.75l.71-.71m1.07 3.8l.97-.25");
}

</style>
