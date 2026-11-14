<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rekrqsbmf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:actuator" /></template>
<style>
.rekrqsbmf {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M5.75 6.25h-1.5q-1.036 0-1.768.732T1.75 8.75v6.5q0 2.5 2.5 2.5h1.5q1.036 0 1.768-.732q.626-.627.717-1.475q.464.207 1.015.207h5.5q1.036 0 1.768-.732t.732-1.768v-.5h3.5v1.75q0 .074.014.146q.015.073.043.141t.069.13t.094.113q.052.053.113.094t.13.069t.141.043t.146.014t.146-.014q.073-.015.141-.043t.13-.069q.061-.041.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146v-5q0-.074-.014-.146q-.015-.073-.043-.141t-.069-.13t-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043t-.146-.014t-.146.014q-.073.015-.141.043t-.13.069q-.061.041-.113.094q-.053.052-.094.113t-.069.13t-.043.141t-.014.146v1.75h-3.5v-.5q0-2.5-2.5-2.5h-5.5q-.579 0-1.024.134q-.109-.802-.708-1.402q-.732-.732-1.768-.732");
}

</style>
