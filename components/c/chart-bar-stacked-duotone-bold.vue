<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="dh-nlhghu"/><path class="jiw8u-asa"/><path class="by8dq9bre"/><path class="pvw7n-bni"/><path class="i43936bdz"/><path class="cfo2f-5oz"/><path class="r3faxubne"/><path class="oifr9zbpt"/><path class="r7dke9bth"/><path class="w8gxvdb9g"/><path class="c2hjexb6t"/><path class="nne1mobhl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:chart-bar-stacked-duotone-bold" /></template>
<style>
.by8dq9bre {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M4 8h7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.c2hjexb6t {
  d: path("M4 14h5");
}

.cfo2f-5oz {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M12 14h5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.dh-nlhghu {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M4 4v16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.i43936bdz {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M4 14h5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.jiw8u-asa {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M4 20h16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.nne1mobhl {
  d: path("M12 14h5");
}

.oifr9zbpt {
  d: path("M4 20h16");
}

.pvw7n-bni {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M14 8h5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.r3faxubne {
  d: path("M4 4v16");
}

.r7dke9bth {
  d: path("M4 8h7");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.w8gxvdb9g {
  d: path("M14 8h5");
}

</style>
