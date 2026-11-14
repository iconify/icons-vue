<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k6g3bftqe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:capacity-low" /></template>
<style>
.k6g3bftqe {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M8.995 2.995Q7.75 4.24 7.75 6t1.245 3.005T12 10.25t3.005-1.245T16.25 6t-1.245-3.005T12 1.75T8.995 2.995M4.25 15.5q0-4 7.75-4t7.75 4q0 .074-.014.146q-.015.073-.043.141t-.069.13t-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069q-.061-.041-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141t-.014-.146q0-2.5-6.25-2.5t-6.25 2.5q0 .074-.014.146q-.015.073-.043.141t-.069.13t-.094.113q-.052.053-.113.094t-.13.069t-.141.043T5 16.25t-.146-.014q-.073-.015-.141-.043t-.13-.069q-.061-.041-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141t-.014-.146m17.5 4.5q0-2.25-2.25-2.25H7q2.25 0 2.25 2.25T7 22.25h12.5q2.25 0 2.25-2.25");
}

</style>
