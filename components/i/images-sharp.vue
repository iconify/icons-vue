<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="ya1jz6bpd"/><path class="zvrb446ow"/><circle class="riv17abjk"/><path class="o2beogbhl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:images-sharp" /></template>
<style>
.o2beogbhl {
  d: path("m2.75 18.5l4-4l1.125-1.112L9 14.5l4.25 4.25M12 17.5l1.6-1.6l1.125-1.112L15.85 15.9l2.4 2.4");
}

.riv17abjk {
  cx: 7.75px;
  cy: 11.25px;
  r: 1.5px;
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ya1jz6bpd {
  d: path("M2.75 6.75h15.5v14.5H2.75z");
}

.zvrb446ow {
  d: path("M6.75 3.75h14.5v13.5");
}

</style>
