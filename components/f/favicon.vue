<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="qw8tp0w0n"/><path class="cj4h9fbbc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:favicon" /></template>
<style>
.cj4h9fbbc {
  d: path("m12.808 8.888l.456 1.065a1.5 1.5 0 0 0 1.244.903l1.153.105a.879.879 0 0 1 .5 1.537l-.872.763a1.5 1.5 0 0 0-.475 1.461l.257 1.13a.879.879 0 0 1-1.308.95l-.994-.593a1.5 1.5 0 0 0-1.538 0l-.994.593a.879.879 0 0 1-1.308-.95l.257-1.13a1.5 1.5 0 0 0-.475-1.461l-.872-.763a.879.879 0 0 1 .5-1.537l1.153-.105a1.5 1.5 0 0 0 1.244-.903l.456-1.065a.879.879 0 0 1 1.616 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.qw8tp0w0n {
  d: path("M2.5 20.5a1 1 0 0 0 1-1V7a3 3 0 0 1 3-3h11a3 3 0 0 1 3 3v12.5a1 1 0 0 0 1 1");
}

</style>
