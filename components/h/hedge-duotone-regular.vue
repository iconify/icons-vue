<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="spx1xqb6w"/><path class="o8hzclkqx"/><path class="jkuojibnm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:hedge-duotone-regular" /></template>
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

.o8hzclkqx {
  d: path("M3 17v-5c0 -4 4 -7 9 -7s9 3 9 7v5Z");
}

.spx1xqb6w {
  fill: currentColor;
  d: path("M3 17v-5c0 -4 4 -7 9 -7s9 3 9 7v5Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
