<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ui8h5iluc"/><path class="ooo6ccsua"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:bbq-restaurant" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ooo6ccsua {
  d: path("M7 20.5V15h4v5.5m3.5-4h7a3.5 3.5 0 0 1-7 0m1.5 2.75l-1 2.5m5-2.5l1 2.5m-4.25-7.25c-.75-1 .75-2 0-3m2.5 3c-.75-1 .75-2 0-3");
}

.ui8h5iluc {
  d: path("M4.75 3h14.5A1.75 1.75 0 0 1 21 4.75v.5A1.75 1.75 0 0 1 19.25 7H4.75A1.75 1.75 0 0 1 3 5.25v-.5A1.75 1.75 0 0 1 4.75 3M4.5 7v13.5h8m7-11.8V7");
}

</style>
