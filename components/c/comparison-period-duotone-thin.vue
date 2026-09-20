<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="gms_xv68n"/><path class="yu-j7jb_g"/><path class="j8fa3wwgn"/><path class="bovqj9b7s"/><path class="r3faxubne"/><path class="oifr9zbpt"/><path class="v7dqcwgbe"/><path class="pl75u7wzh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:comparison-period-duotone-thin" /></template>
<style>
.bovqj9b7s {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m7 10 3 -3 3 3 3 -3 3 3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.gms_xv68n {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M4 4v16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.j8fa3wwgn {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m7 15 3 -3 3 3 3 -3 3 3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.oifr9zbpt {
  d: path("M4 20h16");
}

.pl75u7wzh {
  d: path("m7 10 3 -3 3 3 3 -3 3 3");
}

.r3faxubne {
  d: path("M4 4v16");
}

.v7dqcwgbe {
  d: path("m7 15 3 -3 3 3 3 -3 3 3");
}

.yu-j7jb_g {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M4 20h16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
