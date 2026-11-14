<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="orsyp558p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:colour-mode-rgb" /></template>
<style>
.orsyp558p {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M18.5 3.25h-13q-1.76 0-3.005 1.245T1.25 7.5v6q0 1.76 1.245 3.005T5.5 17.75h5.75v2H8q-.074 0-.146.014q-.073.015-.141.043t-.13.069q-.061.041-.113.094q-.053.052-.094.113t-.069.13t-.043.141t-.014.146q0 .074.014.146q.015.073.043.141t.069.13q.041.061.094.113q.052.053.113.094t.13.069t.141.043t.146.014h8q.074 0 .146-.014q.073-.015.141-.043t.13-.069q.061-.041.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146q0-.074-.014-.146q-.015-.073-.043-.141t-.069-.13q-.041-.061-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043T16 19.75h-3.25v-2h5.75q1.76 0 3.005-1.245T22.75 13.5v-6q0-1.76-1.245-3.005T18.5 3.25m-12.25 5q.932 0 1.591.659T8.5 10.5t-.659 1.591t-1.591.659Q4 12.75 4 10.5t2.25-2.25m8 2.25q0 2.25-2.25 2.25T9.75 10.5T12 8.25t2.25 2.25m3.5-2.25Q20 8.25 20 10.5t-2.25 2.25t-2.25-2.25t2.25-2.25");
}

</style>
