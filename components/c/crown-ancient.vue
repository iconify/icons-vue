<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="myof28bwa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:crown-ancient" /></template>
<style>
.myof28bwa {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M2.25 16v1.75q0 2.5 2.5 2.5h14.5q1.036 0 1.768-.732t.732-1.768v-6.713q.002-1.481-1.366-2.048t-2.414.481l-.783.783q-.362.362-.868.28q-.505-.082-.734-.54l-1.349-2.699Q13.545 5.913 12 5.913T9.764 7.295L8.415 9.993q-.229.458-.734.54q-.506.082-.868-.28l-.782-.783q-1.047-1.048-2.415-.481T2.25 11.036zm0 0q0-.074.014-.146q.015-.073.043-.141t.069-.13t.094-.113q.052-.053.113-.094t.13-.069t.141-.043T3 15.25h18q.074 0 .146.014q.073.015.141.043t.13.069q.061.041.113.094q.053.052.094.113t.069.13t.043.141t.014.146t-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014H3q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141T2.25 16");
}

</style>
