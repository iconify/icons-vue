<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ni1allbsp"/><path class="nmhnie-7b"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:home-alarm-discount" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ni1allbsp {
  d: path("M12.556 19.5H4.25q-.086 0-.172-.008t-.169-.026q-.085-.016-.167-.041t-.162-.058t-.155-.074q-.076-.04-.147-.088q-.072-.048-.138-.102q-.067-.055-.127-.116q-.061-.06-.116-.127q-.054-.066-.102-.138q-.048-.071-.088-.147q-.041-.076-.074-.155q-.033-.08-.058-.162t-.041-.167t-.026-.169q-.008-.086-.008-.172v-7.424q0-.194.042-.383t.126-.364q.082-.175.201-.328t.269-.276l6.75-5.559q.117-.096.248-.171q.131-.074.273-.125t.291-.077t.3-.026t.3.026t.291.077t.273.125t.248.171l6.75 5.559q.15.123.269.276t.201.328t.126.364t.042.383v2.293");
}

.nmhnie-7b {
  d: path("M6 15h6l-1-1.25v-2a2 2 0 0 0-4 0v2Zm8.75 6.25l6.5-6.5m-5.75.75h.01m4.99 5h.01");
}

</style>
