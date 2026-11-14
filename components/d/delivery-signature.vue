<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="kp5id_ban"/><path class="lhecb682t"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:delivery-signature" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.kp5id_ban {
  d: path("M12.9 18H4.25q-.086 0-.172-.008t-.169-.026q-.085-.016-.167-.041t-.162-.058t-.155-.074q-.076-.04-.147-.088q-.072-.048-.138-.102q-.067-.055-.127-.116q-.061-.06-.116-.127q-.054-.066-.102-.138q-.048-.071-.088-.147q-.041-.076-.074-.155q-.033-.08-.058-.162t-.041-.167t-.026-.169q-.008-.086-.008-.172v-7.5q0-.086.008-.172t.026-.169q.016-.085.041-.167t.058-.162q.033-.079.074-.155t.088-.147t.102-.138t.116-.127q.06-.061.127-.116q.066-.054.138-.102q.071-.048.147-.088q.076-.041.155-.074q.08-.033.162-.058t.167-.041t.169-.026Q4.164 7 4.25 7h9.5q.086 0 .172.008t.169.026q.085.016.167.041t.162.058q.079.033.155.074t.147.088t.138.102t.127.116q.061.06.116.127q.054.066.102.138q.048.071.088.147q.041.076.074.155q.033.08.058.162t.041.167t.026.169t.008.172v6.325M2.5 7L6 3.5h13L15.5 7M19 3.5v9.1");
}

.lhecb682t {
  d: path("M5 13.5c1-3 2.25-3 2.75-1s1.75 2 2.5 0S12 11 13 13.25m2.125 7.125l.27-.991a1.5 1.5 0 0 1 .387-.666l2.907-2.907a1.5 1.5 0 0 1 2.122 0l.128.128a1.5 1.5 0 0 1 0 2.122L18.09 20.91a1.5 1.5 0 0 1-.814.419l-1.12.187a.913.913 0 0 1-1.031-1.141M15.5 19l2.25 2.25M18.5 16l2.25 2.25");
}

</style>
