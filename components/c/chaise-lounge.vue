<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vq1t2nbfv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:chaise-lounge" /></template>
<style>
.vq1t2nbfv {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M3 12.75h10.5q.518 0 1.845-2.866q1.753-3.785 3.242-4.116l.04-.008q1.452-.242 2.341.647q.782.782.782 2.093q0 3.094-1.459 5.908q-1.473 2.84-3.541 3.267V19.5q0 .074-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014t-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141t-.014-.146v-1.75h-9.5v1.75q0 .074-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043T5 20.25t-.146-.014q-.073-.015-.141-.043t-.13-.069q-.061-.041-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141t-.014-.146v-1.757q-2-.122-2-2.243v-2q0-.074.014-.146q.015-.073.043-.141t.069-.13t.094-.113q.052-.053.113-.094t.13-.069t.141-.043T3 12.75");
}

</style>
