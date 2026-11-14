<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aqasxnb4i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:exit-arrow-up" /></template>
<style>
.aqasxnb4i {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("m18.439 8.379l-4.672-4.673Q12 1.941 10.233 3.707L5.561 8.379q-.795.794-.365 1.833T6.75 11.25h.5q.414 0 .707.293t.293.707v3q0 2.5 2.5 2.5h2.5q1.036 0 1.768-.732t.732-1.768v-3q0-1 1-1h.5q1.124 0 1.554-1.038t-.365-1.833M20 19.75H4q-.074 0-.146.014q-.073.015-.141.043t-.13.069t-.113.094q-.053.052-.094.113t-.069.13t-.043.141t-.014.146q0 .074.014.146q.015.073.043.141t.069.13q.041.061.094.113q.052.053.113.094t.13.069t.141.043t.146.014h16q.074 0 .146-.014q.073-.015.141-.043t.13-.069q.061-.041.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146q0-.074-.014-.146q-.015-.073-.043-.141t-.069-.13q-.041-.061-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043T20 19.75");
}

</style>
