<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uufp9k86y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:climate-control" /></template>
<style>
.uufp9k86y {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12.959 19H4.25q-.086 0-.172-.008t-.169-.026q-.085-.016-.167-.041t-.162-.058t-.155-.074q-.076-.04-.147-.088q-.072-.048-.138-.102q-.067-.055-.127-.116q-.061-.06-.116-.127q-.054-.066-.102-.138q-.048-.071-.088-.147q-.041-.076-.074-.155q-.033-.08-.058-.162t-.041-.167t-.026-.169q-.008-.086-.008-.172v-6.917q0-.195.043-.385q.043-.191.127-.367t.204-.33t.272-.276l6.25-5.078q.116-.094.247-.168q.13-.073.271-.123t.289-.076t.297-.025t.297.025t.289.076q.141.05.271.123q.131.074.247.168l6.25 5.078q.151.123.272.276q.12.154.204.33t.127.367q.043.19.043.385v.682M7.75 10v9m5.5-9v8m3.5-.25V15a1.25 1.25 0 0 1 2.5 0v2.75a2.25 2.25 0 1 1-2.5 0");
}

</style>
