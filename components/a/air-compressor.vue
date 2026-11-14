<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zodpmwx7o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:air-compressor" /></template>
<style>
.zodpmwx7o {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M8.25 3.25h3.5q2.5 0 2.5 2.5v1q0 2.5-2.5 2.5h-1v1h3.75q1.76 0 3.005 1.245q.971.971 1.185 2.255H19q2.75 0 2.75 2.75v1.354q1 .323 1 1.646v1q0 1.75-1.75 1.75t-1.75-1.75v-1q0-1.323 1-1.646V16.5q0-1.25-1.25-1.25h-.31q-.214 1.284-1.185 2.255T15.25 18.69V21q0 .074-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014t-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141T13.75 21v-2.25h-7V21q0 .074-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043T6 21.75t-.146-.014q-.073-.015-.141-.043t-.13-.069q-.061-.041-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141T5.25 21v-2.31q-1.284-.214-2.255-1.185Q1.75 16.26 1.75 14.5t1.245-3.005T6 10.25h3.25v-1h-1q-2.5 0-2.5-2.5v-1q0-2.5 2.5-2.5");
}

</style>
