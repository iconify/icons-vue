<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="rybdws6oa"/><path class="uyhs3j7ha"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:accountants-office" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.rybdws6oa {
  d: path("M11.441 20H5.25q-.086 0-.172-.008t-.169-.026q-.085-.016-.167-.041t-.162-.058q-.079-.033-.155-.074t-.147-.088q-.072-.048-.138-.102q-.067-.055-.127-.116q-.061-.06-.116-.127q-.054-.066-.102-.138q-.048-.071-.088-.147q-.041-.076-.074-.155q-.033-.08-.058-.162t-.041-.167t-.026-.169q-.008-.086-.008-.172v-7.456q0-.187.04-.37q.039-.183.117-.353q.077-.171.189-.321q.111-.15.252-.273l6.25-5.469q.059-.052.123-.098q.063-.046.131-.087q.067-.04.138-.074t.145-.062t.149-.049t.153-.034q.078-.015.156-.022t.157-.007t.157.007t.156.022t.153.034t.149.049t.145.062t.138.074q.068.041.131.087q.064.046.123.098l6.25 5.469q.135.118.243.261q.109.143.186.305t.119.337q.043.174.049.353");
}

.uyhs3j7ha {
  d: path("M16 13.5h4.25A1.75 1.75 0 0 1 22 15.25v5A1.75 1.75 0 0 1 20.25 22H16a1.75 1.75 0 0 1-1.75-1.75v-5A1.75 1.75 0 0 1 16 13.5m.75 2.75h2.75m-2.75 3h.01m2.74 0h.01");
}

</style>
