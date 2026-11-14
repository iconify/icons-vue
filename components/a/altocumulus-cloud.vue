<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xl08_cctx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:altocumulus-cloud" /></template>
<style>
.xl08_cctx {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M5.25 7q-3.5 0-3.5 3.5q0 .074.014.146q.015.073.043.141t.069.13t.094.113q.052.053.113.094t.13.069t.141.043t.146.014H19q.074 0 .146-.014q.073-.015.141-.043t.13-.069q.061-.041.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146q0-3.5-3.5-3.5q-.965 0-1.664.266q-.379-.8-1.226-1.529q-2.61-2.248-5.22 0q-.847.729-1.226 1.529Q6.215 7 5.25 7m-1.5 11.5q0-3.5 3.5-3.5q.965 0 1.664.266q.379-.8 1.226-1.529q2.61-2.248 5.22 0q.847.729 1.226 1.529Q17.285 15 18.25 15q3.5 0 3.5 3.5q0 .074-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014H4.5q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069q-.061-.041-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141t-.014-.146");
}

</style>
