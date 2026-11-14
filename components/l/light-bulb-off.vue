<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h6tdrj1ya"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:light-bulb-off" /></template>
<style>
.h6tdrj1ya {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M14.038 18H9v-2.5c-2-1.25-3.25-3.25-3.25-5.5q0-.138.006-.276m2.931-5.021q.371-.232.77-.41t.82-.299t.853-.181t.87-.061q.153 0 .307.008q.153.007.305.022q.153.015.305.038q.152.022.302.052t.299.067t.296.082t.291.096t.286.111q.142.058.281.124q.138.066.274.138q.135.072.267.151q.131.079.259.164q.127.085.25.177q.124.091.242.188q.119.098.232.201t.223.211q.108.108.211.222t.201.232q.097.119.188.242q.092.123.177.251q.085.127.164.259q.079.131.151.267q.073.135.138.274q.066.138.125.28t.11.286q.052.144.096.291t.082.296t.068.299t.052.302t.038.305q.015.152.022.305q.008.154.008.307a6.06 6.06 0 0 1-.989 3.308M9.5 21h5M3.5 3.5l17 17");
}

</style>
