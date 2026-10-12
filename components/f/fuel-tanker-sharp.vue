<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="bmk1ugxqj"/><path class="ait4rc48s"/><circle class="pk183qw0r"/><path class="ip1jjbrmk"/><circle class="l991b5b6m"/><path class="s1f9ehlgm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:fuel-tanker-sharp" /></template>
<style>
.ait4rc48s {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8 7.75L6.5 9.5v1.15a1.5 1.5 0 0 0 3 0V9.5zm8.25 6.75v-6h3.205l.445.67l1.1 1.65l.25.368V14.5Zm0-3h4.85m-18.35 3h18.5");
}

.bmk1ugxqj {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 5h10.5v9.5H2.75z");
}

.ip1jjbrmk {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M6.75 19h.01");
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

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

</style>
