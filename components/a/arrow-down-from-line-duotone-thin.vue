<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="o-xue7oyy"/><path class="ctll97b3e"/><path class="ifr8xwb3y"/><path class="t46_l1b3y"/><path class="o8adkomvn"/><path class="qrnoe1--b"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:arrow-down-from-line-duotone-thin" /></template>
<style>
.ctll97b3e {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M12 8v12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ifr8xwb3y {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m8 16 4 4 4 -4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.o-xue7oyy {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M7 4h10");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.o8adkomvn {
  d: path("M12 8v12");
}

.qrnoe1--b {
  d: path("m8 16 4 4 4 -4");
}

.t46_l1b3y {
  d: path("M7 4h10");
}

</style>
