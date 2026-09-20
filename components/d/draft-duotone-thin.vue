<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="etuphyhyp"/><path class="o0lh1k1dl"/><path class="z1t2-_6ze"/><path class="w0as59itk"/><path class="jlfjgzbqx"/><path class="aum97lbyp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:draft-duotone-thin" /></template>
<style>
.aum97lbyp {
  d: path("M9 13h4");
}

.etuphyhyp {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M13 3H6v18h8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jlfjgzbqx {
  d: path("M9 9h6");
}

.o0lh1k1dl {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M9 9h6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.w0as59itk {
  d: path("M13 3H6v18h8");
}

.z1t2-_6ze {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M9 13h4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
