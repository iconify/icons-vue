<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eqf34ewyo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:lights-off-saving" /></template>
<style>
.eqf34ewyo {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M13.1 17H9.25v-1.25c-2-1.25-3.5-3.25-3.5-5.75q0-.135.006-.27m2.925-5.024q.372-.233.772-.411q.4-.179.821-.3t.854-.182t.872-.061q.153 0 .307.008q.153.007.305.022q.153.015.305.038q.152.022.302.052t.299.067t.296.082t.291.096t.286.111q.142.058.281.124q.138.066.274.138q.135.072.267.151q.131.079.259.164q.127.085.25.177q.124.091.242.188q.119.098.232.201t.223.211q.108.108.211.222t.201.232q.097.119.188.242q.092.123.177.251q.085.127.164.259q.079.131.151.267q.073.135.138.274q.066.138.125.28t.11.286q.052.144.096.291t.082.296t.068.299t.052.302t.038.305q.015.152.022.305q.008.154.008.307a6.1 6.1 0 0 1-.984 3.319M9.75 20h4.5M3.5 3.5l17 17");
}

</style>
