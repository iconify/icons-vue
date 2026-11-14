<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xzdcnv5ph"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:magnifying-glass-lab" /></template>
<style>
.xzdcnv5ph {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M2.75 10.5q0-3.21 2.27-5.48t5.48-2.27t5.48 2.27t2.27 5.48q0 2.829-1.762 4.927l4.542 4.543q.053.052.094.113t.069.13t.043.141t.014.146q0 .074-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069q-.061-.041-.113-.094l-4.543-4.542Q13.329 18.25 10.5 18.25q-3.21 0-5.48-2.27T2.75 10.5m1.5 0q0 2.589 1.831 4.419q1.83 1.831 4.419 1.831t4.419-1.831T16.75 10.5t-1.831-4.419Q13.089 4.25 10.5 4.25T6.081 6.081Q4.25 7.911 4.25 10.5m3.599-.176l2.475-2.475q1.414-1.413 2.827-.001q1.413 1.415.001 2.828l-2.476 2.475q-1.414 1.413-2.827.001q-1.413-1.414-.001-2.828z");
}

</style>
