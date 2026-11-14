<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ie5nll_hj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:distributed-tracing" /></template>
<style>
.ie5nll_hj {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M4.75 2.25h6.5q2.5 0 2.5 2.5v.5q0 2.5-2.5 2.5h-5.5v3.5h2.028q.236-2 2.472-2h5q2.5 0 2.5 2.5v.5q0 2.5-2.5 2.5h-5q-2.236 0-2.472-2H5.75v5.5h7.028q.236-2 2.472-2h4q1.036 0 1.768.732t.732 1.768v.5q0 1.036-.732 1.768t-1.768.732h-4q-1.036 0-1.768-.732q-.548-.549-.686-1.268H5q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069q-.061-.041-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141T4.25 19V7.722q-2-.236-2-2.472v-.5q0-2.5 2.5-2.5");
}

</style>
