<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="gxtfwvbwx"/><path class="xr_z7rdvd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:automation-add" /></template>
<style>
.gxtfwvbwx {
  d: path("M6.609 4.727L6.5 4.125a1.465 1.465 0 0 1 1.112-1.689l.635-.147a1.5 1.5 0 0 1 1.73.905l.25.623a1.5 1.5 0 0 0 .98.885l.258.074a1.5 1.5 0 0 0 1.4-.314l.385-.337a1.42 1.42 0 0 1 1.94.065l.62.62a1.42 1.42 0 0 1 .065 1.94l-.337.385a1.5 1.5 0 0 0-.314 1.4l.074.258a1.5 1.5 0 0 0 .885.98l.601.241a1.5 1.5 0 0 1 .898 1.756l-.12.484a1.5 1.5 0 0 1-1.591 1.13l-.771-.07a1.5 1.5 0 0 0-1.197.433l-.256.256a1.5 1.5 0 0 0-.433 1.197l.07.771a1.5 1.5 0 0 1-1.13 1.591l-.484.12a1.5 1.5 0 0 1-1.756-.898l-.241-.601a1.5 1.5 0 0 0-.98-.885l-.258-.074a1.5 1.5 0 0 0-1.4.314l-.385.337a1.42 1.42 0 0 1-1.94-.065l-.62-.62a1.42 1.42 0 0 1-.065-1.94l.337-.385a1.5 1.5 0 0 0 .314-1.4l-.074-.258a1.5 1.5 0 0 0-.885-.98l-.623-.25a1.5 1.5 0 0 1-.905-1.73l.147-.635A1.465 1.465 0 0 1 4.125 6.5l.602.109a1.5 1.5 0 0 0 1.329-.415l.138-.138a1.5 1.5 0 0 0 .415-1.329");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.xr_z7rdvd {
  d: path("M7.25 10a2.75 2.75 0 1 0 5.5 0a2.75 2.75 0 1 0-5.5 0m11.5 5.75v6m-3-3h6");
}

</style>
