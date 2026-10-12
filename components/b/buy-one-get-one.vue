<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="a1tz1fymb"/><path class="n95iwsboj"/><rect class="knw4-wbef"/><path class="t1bn4ibii"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:buy-one-get-one" /></template>
<style>
.a1tz1fymb {
  width: 7px;
  height: 10.25px;
  x: 2.75px;
  y: 11px;
  rx: 1.5px;
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.knw4-wbef {
  width: 7px;
  height: 10.25px;
  x: 14.25px;
  y: 11px;
  rx: 1.5px;
}

.n95iwsboj {
  d: path("M4.75 11V9.75a1.5 1.5 0 0 1 3 0V11");
}

.t1bn4ibii {
  d: path("M16.25 11V9.75a1.5 1.5 0 0 1 3 0V11M12 3.25v3.5M10.25 5h3.5");
}

</style>
