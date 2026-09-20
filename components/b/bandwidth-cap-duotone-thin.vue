<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="u9-qnozzt"/><path class="t0tr22eyz"/><path class="ukvbw5baa"/><path class="r4ocw24za"/><path class="xf07dvr8m"/><path class="ml3aqbbkk"/><path class="rw2cw9fuy"/><path class="pq2hynbuc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:bandwidth-cap-duotone-thin" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ml3aqbbkk {
  d: path("M4 8v12");
}

.pq2hynbuc {
  d: path("m6 18 4 -4 3 3 6 -6");
}

.r4ocw24za {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m6 18 4 -4 3 3 6 -6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.rw2cw9fuy {
  d: path("M4 20h17");
}

.t0tr22eyz {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M4 8v12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.u9-qnozzt {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M2 5h20");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.ukvbw5baa {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M4 20h17");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.xf07dvr8m {
  d: path("M2 5h20");
}

</style>
