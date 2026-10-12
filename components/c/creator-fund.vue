<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="u6y8mqbll"/><rect class="kk1dz_brm"/><path class="tmguoueyk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:creator-fund" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.kk1dz_brm {
  width: 15.5px;
  height: 14.5px;
  x: 4.25px;
  y: 6.75px;
  rx: 3.5px;
}

.tmguoueyk {
  d: path("m12.14 10.57l.82 1.84q.15.32.49.36l2.01.21q.34.03.08.27l-1.49 1.35q-.26.23-.19.57l.42 1.97q.07.35-.23.17L12.3 16.3q-.3-.17-.6 0l-1.75 1.01q-.3.18-.23-.17l.42-1.97q.07-.34-.19-.57l-1.49-1.35q-.26-.24.08-.27l2.01-.21q.34-.04.49-.36l.82-1.84q.14-.32.28 0");
}

.u6y8mqbll {
  d: path("M7.5 3.5h9");
}

</style>
