<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="sxaiolbud"/><path class="ta7myvwbb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:apple-bag" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.sxaiolbud {
  d: path("m10.261 8.07l.156-2.658q.004-.071.015-.141t.028-.139q.018-.068.041-.135t.054-.131q.03-.065.066-.126t.078-.118t.088-.111t.098-.102t.108-.092t.115-.082q.06-.038.123-.07q.064-.033.129-.059q.066-.026.134-.046q.069-.02.138-.033q.07-.014.14-.02q.071-.007.142-.007h7.172q.071 0 .142.007q.07.006.14.02q.069.013.138.033q.068.02.134.046q.065.026.129.059q.063.032.123.07q.059.038.115.082q.056.043.108.092q.051.048.098.102t.088.111q.042.057.078.118t.066.126t.054.131q.023.067.041.135q.017.069.028.139t.015.141l.824 14q.004.076.001.153q-.003.076-.014.152q-.011.075-.03.15q-.019.074-.045.146q-.026.071-.059.14t-.074.134q-.04.065-.086.126q-.047.061-.099.116t-.111.106q-.057.05-.12.094t-.13.081t-.137.067t-.143.054t-.147.038q-.075.016-.151.023q-.077.008-.153.008h-6.563M10.25 7.5h10.5m-14.879.584A3.77 3.77 0 0 0 3.75 7.75q.034.342.111.653");
}

.ta7myvwbb {
  d: path("M8 11.5c-2-1.25-5-.75-5 3C3 18 5.5 21 8 20.25c2.5.75 5-2.25 5-5.75c0-3.75-3-4.25-5-3");
}

</style>
