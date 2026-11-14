<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sz592_q9p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:greenhouse-heater" /></template>
<style>
.sz592_q9p {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12.259 19.5H4.25q-.086 0-.172-.008t-.169-.026q-.085-.016-.167-.041t-.162-.058t-.155-.074q-.076-.04-.147-.088q-.072-.048-.138-.102q-.067-.055-.127-.116q-.061-.06-.116-.127q-.054-.066-.102-.138q-.048-.071-.088-.147q-.041-.076-.074-.155q-.033-.08-.058-.162t-.041-.167t-.026-.169q-.008-.086-.008-.172V9.833q0-.195.043-.385q.043-.191.127-.367t.204-.33t.272-.276l6.25-5.078q.116-.094.247-.168q.13-.073.271-.123t.289-.076t.297-.025t.297.025t.289.076q.141.05.271.123q.131.074.247.168l6.25 5.078q.151.123.272.276q.12.154.204.33t.127.367q.043.19.043.385v.382M2.5 9h16m-8 0v10.5M18 13c1.5 1.75 3 3.25 3 5.5a3 3 0 0 1-6 0c0-1.25.5-2 1.25-2.75c0 1 .5 1.75 1 2c0-1.75.25-3.25.75-4.75");
}

</style>
