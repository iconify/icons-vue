<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ptf22pk2c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:lemon-tree" /></template>
<style>
.ptf22pk2c {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M6.5 16.75q-2.749 0-3.587-2.513q-.736-2.211.769-3.958q-.597-3.039 1.57-4.965q1.977-1.757 4.43-1.183q1.363-1.808 3.791-1.693q2.57.123 3.549 2.334q2.325.198 3.555 2.212q1.288 2.106.264 4.486q1.046 2.054-.231 3.841q-1.338 1.874-3.682 1.439H12.75v4.75q0 .074-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014t-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141t-.014-.146v-4.75zm3.25-9.001v.002q0 .903.826 1.494q.708.506 1.674.506t1.674-.506q.827-.591.826-1.496q.001-.903-.826-1.494q-.708-.506-1.674-.506t-1.674.506q-.826.591-.826 1.494m-4 4.001q0 2 2.5 2t2.5-2t-2.5-2t-2.5 2m7.75 0q0 2 2.5 2t2.5-2t-2.5-2t-2.5 2");
}

</style>
