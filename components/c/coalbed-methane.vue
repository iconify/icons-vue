<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="iuugw5bkk"/><path class="ri3a_miyk"/><path class="bt1wmcbnf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:coalbed-methane" /></template>
<style>
.bt1wmcbnf {
  d: path("m10.5 17.5l9.5-2m-5-13c2.5 2.5 4 5 4 7a4 4 0 0 1-8 0c0-2 1-3.5 2-4.5c.5 1.5 1 2 1.5 2c-.5-2-.5-3.25.5-4.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.iuugw5bkk {
  d: path("m2.322 19.732l.556-3.064a1.5 1.5 0 0 1 .705-1.018l4.011-2.406a1.5 1.5 0 0 1 .878-.21l6.295.449a1.5 1.5 0 0 1 .45.104l4.137 1.655a1.5 1.5 0 0 1 .866.918l1.122 3.366a1.5 1.5 0 0 1-1.423 1.974H3.797a1.5 1.5 0 0 1-1.475-1.768");
}

.ri3a_miyk {
  fill: currentColor;
  d: path("m3.583 15.65l3.087-1.852a1.5 1.5 0 0 1 2.083.558l1.41 2.538a1.5 1.5 0 0 1 .094 1.255l-.892 2.378a1.5 1.5 0 0 1-1.405.973H3.797a1.5 1.5 0 0 1-1.475-1.768l.556-3.064a1.5 1.5 0 0 1 .705-1.018");
}

</style>
