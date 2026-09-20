<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="li5ua4t9f"/><path class="v79iaqbup"/><path class="iyrdq-b5h"/><path class="jiw8u-asa"/><path class="t9gnp4b0n"/><path class="ae-e09b3w"/><path class="a6tpycbpp"/><path class="oifr9zbpt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:beach-trip-duotone-bold" /></template>
<style>
.a6tpycbpp {
  d: path("M12 12v8");
}

.ae-e09b3w {
  d: path("M3 12h18");
}

.iyrdq-b5h {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M12 12v8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.jiw8u-asa {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M4 20h16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.li5ua4t9f {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M3 12a9 9 0 0 1 18 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.oifr9zbpt {
  d: path("M4 20h16");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.t9gnp4b0n {
  d: path("M3 12a9 9 0 0 1 18 0");
}

.v79iaqbup {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M3 12h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
