<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a4z34m35j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:health-dashboard" /></template>
<style>
.a4z34m35j {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M6 2.25h12q1.76 0 3.005 1.245T22.25 6.5V13q0 1.76-1.245 3.005T18 17.25h-5.25v2.5H16q.074 0 .146.014q.073.015.141.043t.13.069q.061.041.113.094q.053.052.094.113t.069.13t.043.141t.014.146q0 .074-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014H8q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069q-.061-.041-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141t-.014-.146q0-.074.014-.146q.015-.073.043-.141t.069-.13q.041-.061.094-.113q.052-.053.113-.094t.13-.069t.141-.043T8 19.75h3.25v-2.5H6q-1.76 0-3.005-1.245T1.75 13V6.5q0-1.76 1.245-3.005T6 2.25m3.75 3h-2.5q-2.5 0-2.5 2.5v4q0 2.5 2.5 2.5h2.5q2.5 0 2.5-2.5v-4q0-2.5-2.5-2.5m3 4.5Q12.75 13 16 13t3.25-3.25T16 6.5t-3.25 3.25");
}

</style>
