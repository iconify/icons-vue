<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="zn6298aab"/><path class="kyrdb7bzq"/><path class="pghnb4t3q"/><path class="amhmhobty"/><path class="i5d2grbwo"/><path class="s27ukbqxc"/><path class="jls6b8fnh"/><path class="l9kfpmzgx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:corpus-add-duotone-thin" /></template>
<style>
.amhmhobty {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M19 2v5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.i5d2grbwo {
  d: path("M13 2H6v14h10V5");
}

.jls6b8fnh {
  d: path("M16.5 4.5h5");
}

.kyrdb7bzq {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M16 8H9v14h10V11");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.l9kfpmzgx {
  d: path("M19 2v5");
}

.pghnb4t3q {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M16.5 4.5h5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.s27ukbqxc {
  d: path("M16 8H9v14h10V11");
}

.zn6298aab {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M13 2H6v14h10V5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
