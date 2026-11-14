<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="du84trbps"/><path class="dprl56bws"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:interview-no-show" /></template>
<style>
.dprl56bws {
  d: path("M18 16v2l1.5 1");
}

.du84trbps {
  d: path("M4.85 3.144za2.25 2.25 0 0 1 2.607 1.825l.868 4.924A2.25 2.25 0 0 1 6.5 12.5a2.25 2.25 0 0 1-2.607-1.825l-.868-4.924A2.25 2.25 0 0 1 4.85 3.144M6.5 12.5l1 1m4.3 3.5H5.25q-.086 0-.172-.008t-.169-.026q-.085-.016-.167-.041t-.162-.058q-.079-.033-.155-.074t-.147-.088q-.072-.048-.138-.102q-.067-.055-.127-.116q-.061-.06-.116-.127q-.054-.066-.102-.138q-.048-.071-.088-.147q-.041-.076-.074-.155q-.033-.08-.058-.162t-.041-.167t-.026-.169q-.008-.086-.008-.172t.008-.172t.026-.169q.016-.085.041-.167t.058-.162q.033-.079.074-.155t.088-.147t.102-.138t.116-.127q.06-.061.127-.116q.066-.054.138-.102q.071-.048.147-.088q.076-.041.155-.074q.08-.033.162-.058t.167-.041q.084-.017.169-.026t.172-.008h8.4M9.5 17v2m-5 2.25l5-2.25l2.569 1.156M14.5 18a3.5 3.5 0 1 0 7 0a3.5 3.5 0 1 0-7 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
