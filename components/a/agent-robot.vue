<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="g53_keb1l"/><rect class="jwglt_bto"/><rect class="fr9aw2b2f"/><path class="gu8uj_bfl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:agent-robot" /></template>
<style>
.fr9aw2b2f {
  width: 10px;
  height: 4.5px;
  x: 7px;
  y: 12.25px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  rx: 2.25px;
}

.g53_keb1l {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 2.85q.24 1.76 2 2q-1.76.24-2 2q-.24-1.76-2-2q1.76-.24 2-2");
}

.gu8uj_bfl {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M9.75 14.5h.01m4.49 0h.01");
}

.jwglt_bto {
  width: 16.5px;
  height: 12.5px;
  x: 3.75px;
  y: 8.75px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  rx: 4.5px;
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
