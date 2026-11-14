<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hlgcz2i0u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:food-truck" /></template>
<style>
.hlgcz2i0u {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M1.75 17V8q0-1.139.805-1.945q.806-.805 1.945-.805H15q.074 0 .146.014q.073.015.141.043t.13.069t.113.094q.053.052.094.113t.069.13t.043.141t.014.146v2.75h2.75q.164 0 .313.069q.15.068.256.193l3 3.5q.088.102.134.228t.047.26v4q0 .074-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014h-1.31q.06.345.06.75q0 2.75-2.75 2.75t-2.75-2.75q0-.405.06-.75H9.69q.06.345.06.75q0 2.75-2.75 2.75T4.25 18.5q0-.405.06-.75H2.5q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141T1.75 17M7.5 8.25q-2.25 0-2.25 2.25v.5q0 .932.659 1.591t1.591.659H10q.932 0 1.591-.659T12.25 11v-.5q0-2.25-2.25-2.25zm13.25 8v-2.973l-2.595-3.027H15.75v5.933q.658-.433 1.75-.433q1.173 0 1.845.5z");
}

</style>
