<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e67kfq7-e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:coverage-improve" /></template>
<style>
.e67kfq7-e {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M11 10.5h.01m3.172-3.182a4.5 4.5 0 0 1 0 6.364m-6.364 0a4.5 4.5 0 0 1 0-6.364M17.01 4.49q.185.185.358.381q.174.196.335.403q.161.206.308.422q.148.216.283.441q.134.224.254.457q.121.232.226.472t.197.484q.091.246.166.496q.076.251.136.506t.104.513t.073.518q.028.26.04.521q.012.262.008.524q-.004.261-.024.522t-.056.52q-.036.26-.088.516M4.99 16.51a8.5 8.5 0 0 1 0-12.02M18 21v-6m-2.5 2.5L18 15l2.5 2.5");
}

</style>
