<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vtprxyb2h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:door-sensor-open" /></template>
<style>
.vtprxyb2h {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M6 2.25h1q1.76 0 3.005 1.245T11.25 6.5v9q0 1.76-1.245 3.005T7 19.75H6q-1.76 0-3.005-1.245T1.75 15.5v-9q0-1.76 1.245-3.005T6 2.25m.51 4H6.5q-.074 0-.146.014q-.073.015-.141.043t-.13.069q-.061.041-.113.094q-.053.052-.094.113t-.069.13t-.043.141T5.75 7t.014.146q.015.073.043.141t.069.13q.041.061.094.113q.052.053.113.094t.13.069t.141.043t.146.014h.01q.074 0 .146-.014q.073-.015.141-.043t.13-.069q.061-.041.113-.094q.053-.052.094-.113t.069-.13t.043-.141Q7.26 7.074 7.26 7t-.014-.146q-.015-.073-.043-.141t-.069-.13q-.041-.061-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043t-.146-.014m14.788 1.952Q20.346 7.25 19 7.25q-3.25 0-3.25 3.25v8q0 1.346.952 2.298T19 21.75t2.298-.952t.952-2.298v-8q0-1.346-.952-2.298");
}

</style>
