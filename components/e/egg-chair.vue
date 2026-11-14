<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y_h14gbhz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:egg-chair" /></template>
<style>
.y_h14gbhz {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M18.616 6.305Q16.465 1.75 12 1.75T5.384 6.305Q3.713 9.843 4.26 13.123q.807 4.841 6.99 5.111v1.516H8.5q-.074 0-.146.014q-.073.015-.141.043t-.13.069t-.113.094q-.053.052-.094.113t-.069.13t-.043.141t-.014.146q0 .074.014.146q.015.073.043.141t.069.13q.041.061.094.113q.052.053.113.094t.13.069t.141.043t.146.014h7q.074 0 .146-.014q.073-.015.141-.043t.13-.069t.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146q0-.074-.014-.146q-.015-.073-.043-.141t-.069-.13q-.041-.061-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043t-.146-.014h-2.75v-1.516q6.183-.27 6.99-5.111q.547-3.28-1.124-6.818M7.25 10q0-2.149 1.361-3.68Q10.006 4.75 12 4.75t3.389 1.57Q16.75 7.851 16.75 10t-1.361 3.68Q13.994 15.25 12 15.25t-3.389-1.57Q7.25 12.149 7.25 10");
}

</style>
