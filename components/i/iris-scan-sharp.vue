<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="i5kn708ng"/><circle class="t6ri8tf6l"/><path class="to8m3ibcr"/><path class="dqyq4fb-l"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:iris-scan-sharp" /></template>
<style>
.dqyq4fb-l {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 7V2.75H7m10 0h4.25V7m0 10v4.25H17m-10 0H2.75V17");
}

.i5kn708ng {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.25 12C6 8.5 8.75 6.5 12 6.5s6 2 7.75 5.5c-1.75 3.5-4.5 5.5-7.75 5.5s-6-2-7.75-5.5Z");
}

.t6ri8tf6l {
  cx: 12px;
  cy: 12px;
  r: 3px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.to8m3ibcr {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 12h.01");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

</style>
