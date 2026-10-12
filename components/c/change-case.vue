<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="tym_h1bsl"/><circle class="t45nmnboy"/><path class="gjxnp4b8z"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:change-case" /></template>
<style>
.gjxnp4b8z {
  d: path("M19.5 7.25v6M4 18.5h16M6.5 16L4 18.5L6.5 21m11-5l2.5 2.5l-2.5 2.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.t45nmnboy {
  cx: 16.5px;
  cy: 10.25px;
  r: 3px;
}

.tym_h1bsl {
  d: path("m3 13.25l4-9.5l4 9.5M4.4 10h5.2");
}

</style>
