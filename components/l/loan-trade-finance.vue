<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="qp_7j5cax"/><path class="nr2kwkbiv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:loan-trade-finance" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.nr2kwkbiv {
  d: path("M17 15h2a3 3 0 0 1 0 6h-2");
}

.qp_7j5cax {
  d: path("M11.418 16.5H5.966q-.107 0-.214-.015q-.106-.016-.209-.046t-.201-.075t-.188-.103q-.091-.058-.172-.128t-.151-.152t-.129-.172t-.102-.188l-1.136-2.5l-.036-.086q-.017-.044-.031-.089t-.025-.09t-.019-.092l-.014-.092l-.008-.094q-.002-.046-.002-.093l.004-.094q.004-.047.01-.093t.016-.092q.009-.046.021-.092q.012-.045.027-.089q.015-.045.032-.088q.018-.044.038-.086t.043-.083t.048-.08t.053-.077t.058-.074t.063-.07q.032-.034.066-.066q.035-.032.071-.061q.036-.03.074-.057t.078-.053q.039-.025.08-.047l.084-.042q.042-.02.086-.037l.088-.032l.09-.026l.092-.02q.046-.009.092-.014q.047-.006.093-.009Q4.783 11 4.83 11h14.34q.072 0 .144.007q.071.007.142.02t.14.035q.069.02.136.047q.066.027.13.06t.125.072q.06.04.116.084t.109.095q.051.05.098.105t.088.113q.042.059.077.122q.036.063.065.128q.03.066.053.134q.022.069.039.139q.016.07.025.141q.01.072.013.144M6 3h1.5A1.5 1.5 0 0 1 9 4.5v5A1.5 1.5 0 0 1 7.5 11H6a1.5 1.5 0 0 1-1.5-1.5v-5A1.5 1.5 0 0 1 6 3m6.5 3.5h6A1.5 1.5 0 0 1 20 8v1.5a1.5 1.5 0 0 1-1.5 1.5h-6A1.5 1.5 0 0 1 11 9.5V8a1.5 1.5 0 0 1 1.5-1.5m-8-.5H9m5 .5V11m3-4.5V11M2.5 20q2.25-1.5 4.5 0t4.5 0m2.5-2a3 3 0 1 0 6 0a3 3 0 1 0-6 0");
}

</style>
