<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="bswuckb7t"/><path class="gotz1cb7r"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:grid-to-home" /></template>
<style>
.bswuckb7t {
  d: path("M12.256 20.5H4.75q-.086 0-.172-.008t-.169-.026q-.085-.016-.167-.041t-.162-.058q-.079-.033-.155-.074t-.147-.088q-.072-.048-.138-.102q-.067-.055-.127-.116q-.061-.06-.116-.127q-.054-.066-.102-.138q-.048-.071-.088-.147q-.041-.076-.074-.155q-.033-.08-.058-.162t-.041-.167t-.026-.169Q3 18.836 3 18.75v-7.924q0-.194.042-.383t.126-.364q.082-.175.201-.328t.269-.276l6.75-5.559q.117-.096.248-.171q.131-.074.273-.125t.291-.077t.3-.026t.3.026t.291.077t.273.125t.248.171l6.75 5.559q.15.123.269.276t.201.328t.126.364t.042.383v.993");
}

.gotz1cb7r {
  d: path("M7.5 20.5v-5H11v5m4-4.25h6m-1.75-1.75L21 16.25m0 3.5h-6m1.75 1.75L15 19.75");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
