<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ws7q_s28g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:licence-key" /></template>
<style>
.ws7q_s28g {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M6.875 4.25h10.25q2.123 0 3.624 1.501t1.501 3.624v5.25q0 2.123-1.501 3.624t-3.624 1.501H6.875q-2.123 0-3.624-1.501T1.75 14.625v-5.25q0-2.123 1.501-3.624T6.875 4.25M4.5 12q0 1.75.875 2.625T8 15.5q3.102 0 3.455-2.75h2.795v2q0 .074.014.146q.015.073.043.141t.069.13t.094.113q.052.053.113.094t.13.069t.141.043t.146.014t.146-.014q.073-.015.141-.043t.13-.069t.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146v-2h1.5v2q0 .074.014.146q.015.073.043.141t.069.13t.094.113q.052.053.113.094t.13.069t.141.043t.146.014t.146-.014q.073-.015.141-.043t.13-.069q.061-.041.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146V12q0-.074-.014-.146q-.015-.073-.043-.141t-.069-.13t-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043T18 11.25h-6.545Q11.102 8.5 8 8.5q-3.5 0-3.5 3.5");
}

</style>
