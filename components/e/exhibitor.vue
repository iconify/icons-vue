<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="jhrobr0da"/><path class="uhkruqb7c"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:exhibitor" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jhrobr0da {
  d: path("M4.25 2.5h14A1.75 1.75 0 0 1 20 4.25v.5a1.75 1.75 0 0 1-1.75 1.75h-14A1.75 1.75 0 0 1 2.5 4.75v-.5A1.75 1.75 0 0 1 4.25 2.5m.25 4v4m13.5-4v4m-6 9H4.25q-.086 0-.172-.008t-.169-.026q-.085-.016-.167-.041t-.162-.058t-.155-.074q-.076-.04-.147-.088q-.072-.048-.138-.102q-.067-.055-.127-.116q-.061-.06-.116-.127q-.054-.066-.102-.138q-.048-.071-.088-.147q-.041-.076-.074-.155q-.033-.08-.058-.162t-.041-.167t-.026-.169q-.008-.086-.008-.172v-5.5q0-.086.008-.172t.026-.169q.016-.085.041-.167t.058-.162q.033-.079.074-.155t.088-.147t.102-.138t.116-.127q.06-.061.127-.116q.066-.054.138-.102q.071-.048.147-.088q.076-.041.155-.074q.08-.033.162-.058t.167-.041t.169-.026t.172-.008h14q.306 0 .595.104q.288.104.524.3M14.5 21.25c0-1.5 1.5-2.5 3.5-2.5s3.5 1 3.5 2.5c0 .25-.25.5-.5.5h-6c-.25 0-.5-.25-.5-.5");
}

.uhkruqb7c {
  d: path("M16.25 15.25a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0");
}

</style>
