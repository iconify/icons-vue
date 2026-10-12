<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><rect class="w4n8xgn0c"/><path class="km__1hbuq"/><circle class="pk183qw0r"/><path class="ip1jjbrmk"/><circle class="l991b5b6m"/><path class="s1f9ehlgm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:fuel-tanker" /></template>
<style>
.ip1jjbrmk {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M6.75 19h.01");
}

.km__1hbuq {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8 7.75s-1.5 1.75-1.5 2.9a1.5 1.5 0 0 0 3 0C9.5 9.5 8 7.75 8 7.75m8.25 6.75v-5a1 1 0 0 1 1-1h1.4a1.5 1.5 0 0 1 1.25.67l1.1 1.65c.17.25.25.55.25.85v2.83Zm0-3h4.85m-18.35 3h18.5");
}

.l991b5b6m {
  cx: 18.25px;
  cy: 19px;
  r: 2.25px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.pk183qw0r {
  cx: 6.75px;
  cy: 19px;
  r: 2.25px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.s1f9ehlgm {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M18.25 19h.01");
}

.w4n8xgn0c {
  width: 10.5px;
  height: 9.5px;
  x: 2.75px;
  y: 5px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  rx: 4px;
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
