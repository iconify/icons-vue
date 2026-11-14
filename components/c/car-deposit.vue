<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="gns0hrb9x"/><path class="f6ykx7bns"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:car-deposit" /></template>
<style>
.f6ykx7bns {
  d: path("M4.75 11a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0m11.512.881q.117-.201.178-.425T16.5 11q0-.086-.008-.172t-.026-.169q-.016-.085-.041-.167t-.058-.162q-.033-.079-.074-.155t-.088-.147t-.102-.138t-.116-.127t-.127-.116q-.066-.054-.138-.102q-.071-.048-.147-.088q-.076-.041-.155-.074q-.08-.033-.162-.058t-.167-.041t-.169-.026t-.172-.008q-.086 0-.172.008t-.169.026q-.085.016-.167.041t-.162.058q-.079.033-.155.074t-.147.088q-.072.048-.138.102q-.067.055-.127.116q-.061.06-.116.127q-.054.066-.102.138q-.048.071-.088.147q-.041.076-.074.155q-.033.08-.058.162t-.041.167t-.026.169T13 11q0 .086.008.172t.026.169q.016.085.041.167t.058.162q.033.079.074.155t.088.147q.048.072.102.138q.055.067.116.127q.06.061.127.116q.066.054.138.102q.071.048.147.088q.076.041.155.074q.08.033.162.058t.167.041t.169.026t.172.008q.224 0 .44-.056m1.31 3.556a2.25 2.25 0 1 0 4.5 0a2.25 2.25 0 1 0-4.5 0m-1.25 5h6.5");
}

.gns0hrb9x {
  d: path("M4.75 11H3.5a1 1 0 0 1-1-1V7.5A1.5 1.5 0 0 1 4 6h1.25L7 3.25a1.5 1.5 0 0 1 1.25-.75h4.5a1.5 1.5 0 0 1 1.25.75L15.75 6H18a1.5 1.5 0 0 1 1.5 1.5V10a1 1 0 0 1-1 1h-2m-8.25 0H13");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
