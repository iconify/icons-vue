<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="m8zldf86r"/><path class="uda6dfbwy"/><path class="kr89xrare"/><path class="dl8beccds"/><path class="ujz4z0bsw"/><path class="b0695_86h"/><path class="ozi-k-boi"/><path class="d23kmtbkz"/><path class="efyfmvbkh"/><path class="x5li7lwaz"/><path class="jwnes9bsk"/><path class="nijl6gb2v"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:judge-model-duotone-bold" /></template>
<style>
.b0695_86h {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M8 19h8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.d23kmtbkz {
  d: path("M9 7a3 3 0 0 1 -6 0");
}

.dl8beccds {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M21 7a3 3 0 0 1 -6 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.efyfmvbkh {
  d: path("M21 7a3 3 0 0 1 -6 0");
}

.jwnes9bsk {
  d: path("M8 19h8");
}

.kr89xrare {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M9 7a3 3 0 0 1 -6 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.m8zldf86r {
  fill: currentColor;
  d: path("M17 8.5a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.nijl6gb2v {
  d: path("M17 8.5a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.ozi-k-boi {
  d: path("M3 7h18");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.uda6dfbwy {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M3 7h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.ujz4z0bsw {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M12 7v12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.x5li7lwaz {
  d: path("M12 7v12");
}

</style>
