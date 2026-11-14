<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ul-o-lb6b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:gavel-block" /></template>
<style>
.ul-o-lb6b {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("m6.581 8.427l4.596-4.596q.732-.733 1.767-.733q1.036 0 1.768.733l.707.707q.733.732.733 1.768q0 1.035-.733 1.767l-1.767 1.768l6.878 6.879q.053.052.094.113t.069.13t.043.141t.014.146q0 .074-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043T20 18t-.146-.014q-.073-.015-.141-.043t-.13-.069q-.061-.041-.113-.094l-6.879-6.878l-1.768 1.767q-.732.733-1.767.733q-1.036 0-1.768-.733l-.707-.707q-.733-.732-.733-1.768q0-1.035.733-1.767M5.25 16.75h7.5q1.036 0 1.768.732t.732 1.768t-.732 1.768t-1.768.732h-7.5q-1.036 0-1.768-.732T2.75 19.25t.732-1.768t1.768-.732");
}

</style>
