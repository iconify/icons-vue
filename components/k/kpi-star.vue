<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="c_cib0b9x"/><path class="rtkq04bgr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:kpi-star" /></template>
<style>
.c_cib0b9x {
  d: path("M13 21H2.5V3h19v10.9M6 6.75h5");
}

.rtkq04bgr {
  d: path("M7.5 15.5v-6l-3 4h4m.75-2.25q0-.086.008-.172t.026-.169q.016-.085.041-.167t.058-.162q.033-.079.074-.155t.088-.147q.048-.072.102-.138q.055-.067.116-.127q.06-.061.127-.116q.066-.054.138-.102q.071-.048.147-.088q.076-.041.155-.074q.08-.033.162-.058t.167-.041t.169-.026T11 9.5q.086 0 .172.008t.169.026q.085.016.167.041t.162.058q.079.033.155.074t.147.088q.072.048.138.102q.067.055.127.116q.061.06.116.127q.054.066.102.138q.048.071.088.147q.041.076.074.155q.033.08.058.162t.041.167t.026.169t.008.172c0 1.409-2.269 2.17-3.153 3.326m-.332.726a1.3 1.3 0 0 0-.015.198h.203M18 14.25l1.029 2.084l2.3.334l-1.665 1.623l.393 2.291L18 19.5l-2.057 1.082l.393-2.291l-1.665-1.623l2.3-.334Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
