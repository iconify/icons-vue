<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hym_czpot"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:hockey-stick-tape" /></template>
<style>
.hym_czpot {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M20.165 3.846L13.75 16.183v2.067q0 1.243-.879 2.121q-.878.879-2.121.879h-5q-1.243 0-2.121-.879q-.879-.878-.879-2.121q0-3 3-3h6.795l6.29-12.096q.068-.132.183-.228t.256-.141t.291-.032t.281.082q.066.034.123.08q.058.046.105.103q.048.056.083.121t.058.135q.022.071.031.144q.008.073.001.147q-.006.074-.027.145t-.055.136M9.75 16.75H8.5v3h1.25zm1.5 2.919q.31-.108.561-.358q.439-.44.439-1.061v-1.5h-1zM7 19.75v-3H5.75q-1.5 0-1.5 1.5q0 .621.439 1.061q.44.439 1.061.439z");
}

</style>
