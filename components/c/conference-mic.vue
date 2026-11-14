<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aweal8bgt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:conference-mic" /></template>
<style>
.aweal8bgt {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M19.755 2.995q.733.732.733 1.767q0 1.036-.733 1.768L17.28 9.005q-.732.733-1.768.733q-.826 0-1.46-.467Q9.75 9.723 9.75 14v2.773q4.5.292 4.5 4.227q0 .074-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014h-9q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069q-.061-.041-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141T3.75 21q0-3.935 4.5-4.227V14q0-5.228 4.843-6.108q-.081-.311-.081-.654q0-1.036.733-1.768l2.475-2.475q.732-.733 1.768-.733q1.035 0 1.767.733");
}

</style>
