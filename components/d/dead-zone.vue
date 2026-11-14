<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bw_psbczq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:dead-zone" /></template>
<style>
.bw_psbczq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m7.5 21l2.552-6.946m6.103 6.007L16.5 21M12.651 8.624q.121-.048.233-.114t.214-.148t.19-.177t.161-.204t.13-.226q.056-.117.094-.242t.058-.254T13.75 7q0-.086-.008-.172t-.026-.169q-.016-.085-.041-.167t-.058-.162q-.033-.079-.074-.155t-.088-.147q-.048-.072-.102-.138q-.055-.067-.116-.127q-.06-.061-.127-.116q-.066-.054-.138-.102q-.071-.048-.147-.088q-.076-.041-.155-.074q-.08-.033-.162-.058t-.167-.041t-.169-.026Q12.086 5.25 12 5.25q-.132 0-.263.02t-.257.059t-.245.097t-.228.133t-.205.165q-.096.091-.178.195q-.082.103-.147.218t-.112.239m4.688-3.015a4.75 4.75 0 0 1 0 7.278M8.15 4.218q.345-.478.797-.857M3.5 3.5l17 17");
}

</style>
