<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="iflob6nfb"/><circle class="o-6fcb5pr"/><path class="q2ijv29-k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:crop-rows" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.iflob6nfb {
  d: path("m3.09 20.53l4.57-9.56q.34-.72 1.14-.72h6.4q.8 0 1.14.72l4.57 9.56q.34.72-.46.72H3.55q-.8 0-.46-.72m4.66.72L9.55 14M12 21.25V14m4.25 7.25L14.45 14");
}

.o-6fcb5pr {
  cx: 16.5px;
  cy: 5px;
  r: 2.25px;
}

.q2ijv29-k {
  d: path("M2.75 10.25h3.5m11.5 0h3.5");
}

</style>
