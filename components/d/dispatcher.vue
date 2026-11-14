<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="u4bxi2bmc"/><path class="oxugco7pb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:dispatcher" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.oxugco7pb {
  d: path("M18.369 13.512q-.099-.058-.189-.127q-.091-.07-.171-.151t-.15-.172q-.069-.091-.126-.19t-.101-.205t-.073-.216t-.044-.223T17.5 12v-.5q0-.086.008-.172t.026-.169q.016-.085.041-.167t.058-.162q.033-.079.074-.155t.088-.147t.102-.138t.116-.127q.06-.061.127-.116q.066-.054.138-.102q.071-.048.147-.088q.076-.041.155-.074q.08-.033.162-.058t.167-.041q.084-.017.169-.026t.172-.008q.086 0 .172.008t.169.026q.085.016.167.041t.162.058t.155.074t.147.088q.072.048.138.102q.067.055.127.116q.061.06.116.127q.054.066.102.138q.048.071.088.147q.041.076.074.155q.033.08.058.162t.041.167t.026.169q.008.086.008.172v.5q0 .121-.017.242q-.017.12-.05.237t-.082.228t-.113.214t-.142.197t-.167.175t-.19.151t-.209.123m-15.28.183V16a3 3 0 0 0 3 3H11m8 3c-1.5-1.5-2.5-2.5-2.5-3.25a2.5 2.5 0 0 1 5 0c0 .75-1 1.75-2.5 3.25");
}

.u4bxi2bmc {
  d: path("M4.75 9.75a7.25 7.25 0 0 1 14.5 0m-14.5 0zA1.75 1.75 0 0 1 6.5 11.5v.5a1.75 1.75 0 0 1-1.75 1.75A1.75 1.75 0 0 1 3 12v-.5a1.75 1.75 0 0 1 1.75-1.75");
}

</style>
