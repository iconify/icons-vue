<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gl-7oac_c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:angle-grinder" /></template>
<style>
.gl-7oac_c {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M6.25 5v4.75H5q-3.25 0-3.25 3.25q0 1.346.952 2.298T5 16.25h4q1.515 0 2.324-.707q.409.822 1.11 1.523q1.684 1.684 4.066 1.684t4.066-1.684T22.25 13t-1.684-4.066T16.5 7.25t-4.066 1.684q-.701.701-1.11 1.523Q10.515 9.75 9 9.75H7.75V5q0-.074-.014-.146q-.015-.073-.043-.141t-.069-.13q-.041-.061-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043T7 4.25t-.146.014q-.073.015-.141.043t-.13.069q-.061.041-.113.094q-.053.052-.094.113t-.069.13t-.043.141T6.25 5m8 8q0-2.25 2.25-2.25T18.75 13t-2.25 2.25T14.25 13");
}

</style>
