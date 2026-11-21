<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="b93g55bpi"/><path class="fn6azob7b"/><path class="d1lbhekow"/><path class="q-p4atbce"/><path class="p86kdobof"/><path class="ahifgvjyk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:bow-arrow-broken" /></template>
<style>
.ahifgvjyk {
  d: path("M8.06503 15.9353L6.12053 15.8292C5.55483 15.8292 5.16593 16.1474 4.67093 16.6424L3.11533 18.198C2.72633 18.587 3.00923 19.0819 3.57493 19.0819H4.91843V20.4254C4.91843 20.9911 5.41333 21.274 5.80233 20.885L7.35793 19.3294C7.85293 18.8344 8.17113 18.4455 8.17113 17.8798L8.06503 15.9353Z");
}

.b93g55bpi {
  d: path("M4.86523 5.1353C5.75833 4.1785 6.99723 3.5878 8.39053 3.3472");
}

.d1lbhekow {
  d: path("M4.86523 5.13531L8.06523 15.9353L18.8652 19.1353");
}

.fn6azob7b {
  d: path("M11.5742 3.36679C13.7185 3.72869 15.8954 4.76679 17.5639 6.43529C21.2639 10.1353 21.8639 16.3353 18.8639 19.1353");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.p86kdobof {
  d: path("M17.0645 2.9353H20.3645C20.7511 2.9353 21.0645 3.2487 21.0645 3.6353V6.9353");
}

.q-p4atbce {
  d: path("M8.06445 15.9353L20.8595 3.14029");
}

</style>
