<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ccb_9aigv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:data-mapping" /></template>
<style>
.ccb_9aigv {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M4 2.75h2q2.051 0 2.232 1.869L12 7.55l3.768-2.931Q15.949 2.75 18 2.75h2q2.25 0 2.25 2.25T20 7.25h-2q-1.452 0-1.967-.937L13.222 8.5l2.811 2.187Q16.548 9.75 18 9.75h2q2.25 0 2.25 2.25T20 14.25h-2q-2.051 0-2.232-1.869L12 9.45l-3.768 2.931Q8.051 14.25 6 14.25H4q-2.25 0-2.25-2.25T4 9.75h2q1.452 0 1.967.937L10.778 8.5L7.967 6.313Q7.452 7.25 6 7.25H4Q1.75 7.25 1.75 5T4 2.75m0 14h2q1.837 0 2.174 1.5h7.652q.337-1.5 2.174-1.5h2q2.25 0 2.25 2.25T20 21.25h-2q-1.837 0-2.174-1.5H8.174q-.337 1.5-2.174 1.5H4q-2.25 0-2.25-2.25T4 16.75");
}

</style>
