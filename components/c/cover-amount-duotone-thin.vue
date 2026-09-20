<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="com6fnbxh"/><path class="t9gnp4b0n"/><path class="ae-e09b3w"/><path class="ohhz_s35v"/><path class="yb0sj-xar"/><path class="rju00-nqb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:cover-amount-duotone-thin" /></template>
<style>
.ae-e09b3w {
  d: path("M3 12h18");
}

.com6fnbxh {
  fill: currentColor;
  d: path("m12 5.5 2 2 -2 2 -2 -2Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ohhz_s35v {
  d: path("M12 12v6");
}

.rju00-nqb {
  d: path("m12 5.5 2 2 -2 2 -2 -2Z");
}

.t9gnp4b0n {
  d: path("M3 12a9 9 0 0 1 18 0");
}

.yb0sj-xar {
  d: path("M12 18a2 2 0 0 1 -4 0");
}

</style>
