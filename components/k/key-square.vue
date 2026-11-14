<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u9d_y6b9u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:key-square" /></template>
<style>
.u9d_y6b9u {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M7.375 2.25h9.25q2.123 0 3.624 1.501t1.501 3.624v9.25q0 2.123-1.501 3.624t-3.624 1.501h-9.25q-2.123 0-3.624-1.501T2.25 16.625v-9.25q0-2.123 1.501-3.624T7.375 2.25M8.5 8.75q-3.25 0-3.25 3.25t3.25 3.25q2.85 0 3.201-2.5h2.549v2q0 .074.014.146q.015.073.043.141t.069.13t.094.113q.052.053.113.094t.13.069t.141.043t.146.014t.146-.014q.073-.015.141-.043t.13-.069t.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146v-2h1.5V15q0 .074.014.146q.015.073.043.141t.069.13t.094.113q.052.053.113.094t.13.069t.141.043t.146.014t.146-.014q.073-.015.141-.043t.13-.069q.061-.041.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146v-3q0-.074-.014-.146q-.015-.073-.043-.141t-.069-.13t-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043T18 11.25h-6.299q-.351-2.5-3.201-2.5");
}

</style>
