<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="dh-nlhghu"/><path class="jiw8u-asa"/><path class="z46-rl59e"/><path class="z5yq3bb7n"/><path class="r3faxubne"/><path class="oifr9zbpt"/><path class="v7dqcwgbe"/><path class="pl75u7wzh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:comparison-period-duotone-bold" /></template>
<style>
.dh-nlhghu {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M4 4v16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.jiw8u-asa {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M4 20h16");
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

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.v7dqcwgbe {
  d: path("m7 15 3 -3 3 3 3 -3 3 3");
}

.z46-rl59e {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m7 15 3 -3 3 3 3 -3 3 3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.z5yq3bb7n {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m7 10 3 -3 3 3 3 -3 3 3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
