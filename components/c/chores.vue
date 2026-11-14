<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="bmhmflb2b"/><path class="j5e69bfrn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:chores" /></template>
<style>
.bmhmflb2b {
  d: path("M13.311 20.5H4.25q-.086 0-.172-.008t-.169-.026q-.085-.016-.167-.041t-.162-.058t-.155-.074q-.076-.04-.147-.088q-.072-.048-.138-.102q-.067-.055-.127-.116q-.061-.06-.116-.127q-.054-.066-.102-.138q-.048-.071-.088-.147q-.041-.076-.074-.155q-.033-.08-.058-.162t-.041-.167t-.026-.169q-.008-.086-.008-.172v-8.006q0-.176.035-.349t.105-.336t.169-.307q.1-.146.227-.268l5-4.815q.06-.058.126-.11q.066-.053.136-.098t.145-.084t.153-.071t.158-.055t.163-.04t.166-.024t.167-.008t.167.008t.166.024t.163.04t.158.055q.078.032.153.071q.074.038.145.084q.07.045.136.098q.066.052.126.11l5 4.815q.127.122.227.268q.1.145.169.307q.069.163.105.336t.035.349v3.82");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.j5e69bfrn {
  d: path("M7.5 20.5v-4H11v4m8-9.5v6m-2.844 2.675l.333-1.5A1.5 1.5 0 0 1 17.953 17h2.026a1.5 1.5 0 0 1 1.48 1.253l.25 1.5a1.5 1.5 0 0 1-1.48 1.747H17.62a1.5 1.5 0 0 1-1.464-1.825");
}

</style>
