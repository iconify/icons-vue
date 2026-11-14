<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u346uqb1d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:construction-progress" /></template>
<style>
.u346uqb1d {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M10 1.75H8Q5.75 1.75 5.75 4v2q0 .413.076.75H5.5q-.932 0-1.591.659T3.25 9v2q0 .932.659 1.591t1.591.659h2q.869 0 1.5-.572q.631.572 1.5.572h2q.932 0 1.591-.659T14.75 11V9q0-.932-.659-1.591T12.5 6.75h-.326q.076-.337.076-.75V4q0-2.25-2.25-2.25m-4.5 13h13q3.75 0 3.75 3.75t-3.75 3.75h-13q-3.75 0-3.75-3.75t3.75-3.75m9.75 3.75q0-.074-.014-.146q-.015-.073-.043-.141t-.069-.13q-.041-.061-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043t-.146-.014h-9q-.074 0-.146.014q-.073.015-.141.043t-.13.069q-.061.041-.113.094q-.053.052-.094.113t-.069.13t-.043.141t-.014.146q0 .074.014.146q.015.073.043.141t.069.13q.041.061.094.113q.052.053.113.094t.13.069t.141.043t.146.014h9q.074 0 .146-.014q.073-.015.141-.043t.13-.069t.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146");
}

</style>
