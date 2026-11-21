<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="a1niyeb3g"/><path class="d1lbhekow"/><path class="q-p4atbce"/><path class="p86kdobof"/><path class="ahifgvjyk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:bow-arrow-linear" /></template>
<style>
.a1niyeb3g {
  d: path("M4.86523 5.13531C7.66523 2.13531 13.8652 2.73531 17.5652 6.43531C21.2652 10.1353 21.8652 16.3353 18.8652 19.1353");
}

.ahifgvjyk {
  d: path("M8.06503 15.9353L6.12053 15.8292C5.55483 15.8292 5.16593 16.1474 4.67093 16.6424L3.11533 18.198C2.72633 18.587 3.00923 19.0819 3.57493 19.0819H4.91843V20.4254C4.91843 20.9911 5.41333 21.274 5.80233 20.885L7.35793 19.3294C7.85293 18.8344 8.17113 18.4455 8.17113 17.8798L8.06503 15.9353Z");
}

.d1lbhekow {
  d: path("M4.86523 5.13531L8.06523 15.9353L18.8652 19.1353");
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
