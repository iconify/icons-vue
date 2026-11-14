<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ytee0j2_m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:baby-bib" /></template>
<style>
.ytee0j2_m {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M20.137 16.52q1.73-4.477-.389-9.674Q19.616 2.5 12 2.5T4.252 6.846q-2.119 5.197-.389 9.674q2.02 5.23 8.137 5.23t8.137-5.23M8 6.25H5.862Q6.587 4 12 4t6.138 2.25H16q-.074 0-.146.014q-.073.015-.141.043t-.13.069t-.113.094q-.053.052-.094.113t-.069.13t-.043.141T15.25 7q0 3.25-3.25 3.25T8.75 7q0-.074-.014-.146q-.015-.073-.043-.141t-.069-.13q-.041-.061-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043T8 6.25");
}

</style>
