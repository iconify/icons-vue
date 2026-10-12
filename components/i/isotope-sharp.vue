<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="lp7tzfbll"/><path class="t-0zppsov"/><path class="v8-9ty9fk"/><circle class="f2k4gu_jx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:isotope-sharp" /></template>
<style>
.f2k4gu_jx {
  cx: 17.375px;
  cy: 10.52px;
  r: 2.25px;
}

.lp7tzfbll {
  d: path("M4.46 11.15a2.25 2.25 0 1 1 4.33 0a2.25 2.25 0 1 1-2.16 3.74a2.25 2.25 0 1 1-2.17-3.74Z");
}

.t-0zppsov {
  d: path("m6.63 14.89l-.898-.934l.358-1.246l-1.267-.308l-.363-1.252m4.33 0l-.363 1.252l-1.267.308l-.535.131l-.535-.131m11.29 2.18a2.25 2.25 0 1 1-2.17-3.74l.363 1.252l1.267.308l.535.131l.535-.131l1.267-.308l.363-1.252a2.25 2.25 0 1 1-2.16 3.74Z");
}

.v8-9ty9fk {
  d: path("m17.38 14.89l-.898-.934l.358-1.246");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
