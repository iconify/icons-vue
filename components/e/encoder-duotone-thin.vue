<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ixcncacmy"/><path class="p-hshlbhd"/><path class="bwuo0ywji"/><path class="ps3-67b_v"/><path class="wlia6bb5b"/><path class="adiugjbhs"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:encoder-duotone-thin" /></template>
<style>
.adiugjbhs {
  d: path("m15 9 3 3 -3 3");
}

.bwuo0ywji {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m15 9 3 3 -3 3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ixcncacmy {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m4 3 6 6v6l-6 6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.p-hshlbhd {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M11 12h7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.ps3-67b_v {
  d: path("m4 3 6 6v6l-6 6");
}

.wlia6bb5b {
  d: path("M11 12h7");
}

</style>
