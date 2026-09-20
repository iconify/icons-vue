<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="rjl8fe1sw"/><path class="qq9-4ficr"/><path class="jkuojibnm"/><path class="o1o-p0bmq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:admission-webhook-outline-regular" /></template>
<style>
.jkuojibnm {
  d: path("M3 20h18");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.o1o-p0bmq {
  d: path("m19 7 -4 4h3l-4 4");
}

.qq9-4ficr {
  d: path("m4 13 9 -9");
}

.rjl8fe1sw {
  d: path("M4 6v14");
}

</style>
