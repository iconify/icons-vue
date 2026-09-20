<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="i6fwf7hbu"/><path class="lgpnhhbhj"/><path class="c2t_nhe0e"/><path class="wsird7b6w"/><path class="lob-p4n4f"/><path class="rk3avflyg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:investment-goal-duotone-thin" /></template>
<style>
.c2t_nhe0e {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M18 6h4v3.5h-4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.i6fwf7hbu {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m2 21 5 -5 4 4 7 -7 4 4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.lgpnhhbhj {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M18 5v8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.lob-p4n4f {
  d: path("M18 5v8");
}

.rk3avflyg {
  d: path("M18 6h4v3.5h-4");
}

.wsird7b6w {
  d: path("m2 21 5 -5 4 4 7 -7 4 4");
}

</style>
