<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dm2ff7qmb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:hand-stamp" /></template>
<style>
.dm2ff7qmb {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M12 3.25q-3.5 0-3.5 3.5q0 2.113 1.276 2.95q-.276.512-.276 1.3v1q0 .413.076.75H6.75q-2.5 0-2.5 2.5t2.5 2.5h10.5q2.5 0 2.5-2.5t-2.5-2.5h-2.826q.076-.337.076-.75v-1q0-.788-.276-1.3Q15.5 8.863 15.5 6.75q0-3.5-3.5-3.5m9 16q.074 0 .146.014q.073.015.141.043t.13.069q.061.041.113.094q.053.052.094.113t.069.13t.043.141t.014.146q0 .074-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014H3q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141T2.25 20t.014-.146q.015-.073.043-.141t.069-.13q.041-.061.094-.113q.052-.053.113-.094t.13-.069t.141-.043T3 19.25z");
}

</style>
