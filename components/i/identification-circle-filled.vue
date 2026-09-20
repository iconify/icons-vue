<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":26,"height":26};
const content = `<defs><path id="SVGsu7EwcfJ" class="qua3zr46n"/></defs><g class="ft5dv1b6b"><defs><mask id="SVGj2MxKDsR"><path class="k5-vjlrin"/><g transform="translate(3 3)"><path class="xkx788b5j"/><circle class="a5xvgfrws"/><use href="#SVGsu7EwcfJ"/><rect class="ad_t0pbus"/><path clip-rule="evenodd" class="z5zoidiyp"/><path class="of5ls593o"/><use href="#SVGsu7EwcfJ"/><path clip-rule="evenodd" class="ngosed07l"/></g></mask></defs><circle mask="url(#SVGj2MxKDsR)" class="bd9gczbnq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons-pop:identification-circle-filled" /></template>
<style>
.a5xvgfrws {
  cx: 6.5px;
  cy: 9.25px;
  r: 1.25px;
  fill: var(--svg-color--000, #000);
}

.ad_t0pbus {
  width: 16px;
  height: 11px;
  x: 2px;
  y: 4.5px;
  stroke: var(--svg-color--000, #000);
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  rx: 2px;
}

.bd9gczbnq {
  cx: 13px;
  cy: 13px;
  r: 13px;
  fill: currentColor;
}

.ft5dv1b6b {
  fill: none;
}

.k5-vjlrin {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h26v26H0z");
}

.ngosed07l {
  fill: var(--svg-color--000, #000);
  fill-rule: evenodd;
  d: path("M1 6.5a3 3 0 0 1 3-3h12a3 3 0 0 1 3 3v7a3 3 0 0 1-3 3H4a3 3 0 0 1-3-3zm3-1a1 1 0 0 0-1 1v7a1 1 0 0 0 1 1h12a1 1 0 0 0 1-1v-7a1 1 0 0 0-1-1z");
}

.of5ls593o {
  fill: var(--svg-color--000, #000);
  d: path("M7.75 9.25a1.25 1.25 0 1 1-2.5 0a1.25 1.25 0 0 1 2.5 0");
}

.qua3zr46n {
  fill: var(--svg-color--000, #000);
  d: path("M8 11.628c0 .63-.672.57-1.5.57s-1.5.06-1.5-.57c0-.631.672-1.428 1.5-1.428s1.5.797 1.5 1.428");
}

.xkx788b5j {
  stroke: var(--svg-color--000, #000);
  stroke-linecap: round;
  d: path("M9.5 8H12m-2.5 3.75h5m-5-2.5h5m-5 1.25h5");
}

.z5zoidiyp {
  fill: var(--svg-color--000, #000);
  fill-rule: evenodd;
  d: path("M9 8a.5.5 0 0 1 .5-.5H12a.5.5 0 0 1 0 1H9.5A.5.5 0 0 1 9 8m0 3.75a.5.5 0 0 1 .5-.5h5a.5.5 0 0 1 0 1h-5a.5.5 0 0 1-.5-.5m0-2.5a.5.5 0 0 1 .5-.5h5a.5.5 0 0 1 0 1h-5a.5.5 0 0 1-.5-.5m0 1.25a.5.5 0 0 1 .5-.5h5a.5.5 0 0 1 0 1h-5a.5.5 0 0 1-.5-.5");
}

</style>
