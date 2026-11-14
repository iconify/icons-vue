<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b-ntmsbfz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:e-unicycle" /></template>
<style>
.b-ntmsbfz {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M6.25 4.5q0-2.75 5.75-2.75t5.75 2.75q0 .074-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043T17 5.25h-4.25v1.031q2.833.239 4.907 2.312Q20 10.936 20 14.25t-2.343 5.657T12 22.25t-5.657-2.343T4 14.25t2.343-5.657Q8.417 6.52 11.25 6.281V5.25H7q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069q-.061-.041-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141T6.25 4.5m2.5 8.75v2q0 2.5 2.5 2.5h1.5q1.036 0 1.768-.732t.732-1.768v-2q0-1.036-.732-1.768t-1.768-.732h-1.5q-2.5 0-2.5 2.5");
}

</style>
