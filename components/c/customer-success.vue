<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="n7tzrwbuy"/><path class="lzufm7avf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:customer-success" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.lzufm7avf {
  d: path("M7 5H5.5a2 2 0 0 0 0 4h1.75M17 5h1.5a2 2 0 0 1 0 4h-1.75M12 13v4.5m1.8 3.5H9.25q-.086 0-.172-.008t-.169-.026q-.085-.016-.167-.041t-.162-.058q-.079-.033-.155-.074t-.147-.088t-.138-.102t-.127-.116q-.061-.06-.116-.127q-.054-.066-.102-.138q-.048-.071-.088-.147q-.041-.076-.074-.155q-.033-.08-.058-.162t-.041-.167t-.026-.169q-.008-.086-.008-.172t.008-.172q.009-.085.026-.169q.016-.085.041-.167t.058-.162t.074-.155t.088-.147t.102-.138t.116-.127t.127-.116q.066-.054.138-.102q.071-.048.147-.088q.076-.041.155-.074q.08-.033.162-.058t.167-.041t.169-.026q.086-.008.172-.008h2.7m2.8.5l2 2L21 15.75");
}

.n7tzrwbuy {
  d: path("M7 3h10v5A5 5 0 0 1 7 8Z");
}

</style>
