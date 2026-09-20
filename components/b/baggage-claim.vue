<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<defs><path id="SVGfWQRIDOy" class="pb3_1lbls"/></defs><path class="xa621_ukv"/><path class="ru3fgc3mv"/><use href="#SVGfWQRIDOy" class="e0ty9gbgt"/><g class="y_9pn2b8h"><circle class="l-tj-kdqp"/><circle class="rb5d3nb0x"/><circle class="qth9amood"/><circle class="s4pi5cc-z"/><circle class="me2vbqk-p"/><path class="obhqmcjgn"/></g><use href="#SVGfWQRIDOy" class="pfsdhbbki"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noto:baggage-claim" /></template>
<style>
.e0ty9gbgt {
  opacity: var(--svg-opacity--0-65, 0.65);
}

.l-tj-kdqp {
  cx: 20.54px;
  cy: 102.46px;
  r: 5.78px;
}

.me2vbqk-p {
  cx: 81.23px;
  cy: 102.46px;
  r: 5.78px;
}

.obhqmcjgn {
  d: path("M77.38 24.43c0-4.79-3.88-8.67-8.67-8.67H53.29c-4.79 0-8.67 3.88-8.67 8.67v1.93c0 .53-.43.96-.96.96h-3.85c-1.06 0-1.93.87-1.93 1.93v57.8c0 1.06.87 1.93 1.93 1.93H82.2c1.06 0 1.93-.87 1.93-1.93v-57.8c0-1.06-.87-1.93-1.93-1.93h-3.85a.96.96 0 0 1-.96-.96v-1.93zm-27.94 0c0-2.13 1.72-3.85 3.85-3.85H68.7c2.13 0 3.85 1.72 3.85 3.85v1.93c0 .53-.43.96-.96.96H50.4a.96.96 0 0 1-.96-.96zm-34.68 10.6v46.24c0 4.26 3.45 7.71 7.71 7.71h5.78c1.06 0 1.93-.87 1.93-1.93v-57.8c0-1.06-.87-1.93-1.93-1.93h-5.78c-4.26 0-7.71 3.45-7.71 7.71m84.78-7.71h-5.78c-1.06 0-1.93.87-1.93 1.93v57.8c0 1.06.87 1.93 1.93 1.93h5.78c4.26 0 7.71-3.45 7.71-7.71V35.03c-.01-4.26-3.46-7.71-7.71-7.71");
}

.pb3_1lbls {
  fill: var(--svg-color--68abe6, #68abe6);
  d: path("M39.7 12.9c0-2.3-1.6-3-10.8-2.7c-7.7.3-11.5 1.2-13.8 4c-1.9 2.3-2.3 5.6-2.6 8.4c-.2 2.2-2.2 14.9 3.5 11.2c.68-.45 1.23-1.07 1.6-1.8c1.2-2.1 1.9-3.5 3.3-5.6c5.3-8.6 18.8-10.5 18.8-13.5");
}

.pfsdhbbki {
  opacity: var(--svg-opacity--0-3, 0.3);
}

.qth9amood {
  cx: 61px;
  cy: 102.46px;
  r: 5.78px;
}

.rb5d3nb0x {
  cx: 40.77px;
  cy: 102.46px;
  r: 5.78px;
}

.ru3fgc3mv {
  fill: var(--svg-color--2262dd, #2262dd);
  d: path("M109.7 4H11.5A7.555 7.555 0 0 0 4 11.5v97.9c-.01 4.14 3.34 7.49 7.48 7.5h98.12c4.14.01 7.49-3.34 7.5-7.48V11.5c.09-4.05-3.13-7.41-7.18-7.5z");
}

.s4pi5cc-z {
  cx: 101.46px;
  cy: 102.46px;
  r: 5.78px;
}

.xa621_ukv {
  fill: var(--svg-color--194fa5, #194fa5);
  d: path("M116 4H12c-4.42 0-8 3.58-8 8v104c0 4.42 3.58 8 8 8h104c4.42 0 8-3.58 8-8V12c0-4.42-3.58-8-8-8");
}

.y_9pn2b8h {
  fill: var(--svg-color--fafafa, #fafafa);
}

</style>
