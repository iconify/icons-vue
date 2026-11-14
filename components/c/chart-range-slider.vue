<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d345q00rj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:chart-range-slider" /></template>
<style>
.d345q00rj {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M3.545 11.25Q3.898 8.5 7 8.5q1.45 0 2.475 1.025q.305.306.52.649Q10.411 10 11 10h2q.452 0 .833.175Q14.579 8.5 17 8.5q3.102 0 3.455 2.75H21.5q.074 0 .146.014q.073.015.141.043t.13.069q.061.041.113.094q.053.052.094.113t.069.13t.043.141t.014.146t-.014.146q-.015.073-.043.141t-.069.13t-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014h-1.045Q20.102 15.5 17 15.5q-2.421 0-3.167-1.675Q13.452 14 13 14h-2q-.589 0-1.005-.174q-.215.343-.52.649Q8.45 15.5 7 15.5q-3.102 0-3.455-2.75H2.5q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141Q1.75 12.074 1.75 12t.014-.146q.015-.073.043-.141t.069-.13t.094-.113q.052-.053.113-.094t.13-.069t.141-.043t.146-.014z");
}

</style>
