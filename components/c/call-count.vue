<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="da5enxb5n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:call-count" /></template>
<style>
.da5enxb5n {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M14.548 14.141c2.506-2.483 4.074-5.925 4.202-9.891q0-.086-.008-.172t-.026-.169q-.016-.085-.041-.167t-.058-.162t-.074-.155q-.04-.076-.088-.147q-.048-.072-.102-.138q-.055-.067-.116-.127q-.06-.061-.127-.116q-.066-.054-.138-.102q-.071-.048-.147-.088q-.076-.041-.155-.074q-.08-.033-.162-.058t-.167-.041t-.169-.026Q17.086 2.5 17 2.5h-3l-1.25 4l1.75 1.25C13.5 10.25 11 13 8.75 14L7.5 12.25l-4 1.25v3q0 .086.008.172t.026.169q.016.085.041.167t.058.162t.074.155t.088.147t.102.138t.116.127q.06.061.127.116q.066.054.138.102q.071.048.147.088q.076.041.155.074q.08.033.162.058t.167.041q.084.017.169.026t.172.008c3.299-.22 6.26-1.456 8.562-3.431M16 16.5v5m2.75-5v5m2.75-5v5");
}

</style>
