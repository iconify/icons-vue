<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bff78_ekg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:chart-icicle" /></template>
<style>
.bff78_ekg {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.25 2.5h15.5a1.75 1.75 0 0 1 1.75 1.75v1A1.75 1.75 0 0 1 19.75 7H4.25A1.75 1.75 0 0 1 2.5 5.25v-1A1.75 1.75 0 0 1 4.25 2.5m0 7H9a1.75 1.75 0 0 1 1.75 1.75v1A1.75 1.75 0 0 1 9 14H4.25a1.75 1.75 0 0 1-1.75-1.75v-1A1.75 1.75 0 0 1 4.25 9.5M15 9.5h4.75a1.75 1.75 0 0 1 1.75 1.75v1A1.75 1.75 0 0 1 19.75 14H15a1.75 1.75 0 0 1-1.75-1.75v-1A1.75 1.75 0 0 1 15 9.5m-11.125 7za1.375 1.375 0 0 1 1.375 1.375v2.25A1.375 1.375 0 0 1 3.875 21.5A1.375 1.375 0 0 1 2.5 20.125v-2.25A1.375 1.375 0 0 1 3.875 16.5m5.5 0za1.375 1.375 0 0 1 1.375 1.375v2.25A1.375 1.375 0 0 1 9.375 21.5A1.375 1.375 0 0 1 8 20.125v-2.25A1.375 1.375 0 0 1 9.375 16.5m5.25 0zA1.375 1.375 0 0 1 16 17.875v2.25a1.375 1.375 0 0 1-1.375 1.375a1.375 1.375 0 0 1-1.375-1.375v-2.25a1.375 1.375 0 0 1 1.375-1.375m5.5 0za1.375 1.375 0 0 1 1.375 1.375v2.25a1.375 1.375 0 0 1-1.375 1.375a1.375 1.375 0 0 1-1.375-1.375v-2.25a1.375 1.375 0 0 1 1.375-1.375");
}

</style>
