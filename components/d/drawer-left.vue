<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uqbasdb7i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:drawer-left" /></template>
<style>
.uqbasdb7i {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M6 2.75h12q1.76 0 3.005 1.245T22.25 7v10q0 1.76-1.245 3.005T18 21.25H6q-1.76 0-3.005-1.245T1.75 17V7q0-1.76 1.245-3.005T6 2.75M7 14v-4q0-.074-.014-.146q-.015-.073-.043-.141t-.069-.13t-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043t-.146-.014t-.146.014q-.073.015-.141.043t-.13.069q-.061.041-.113.094q-.053.052-.094.113t-.069.13t-.043.141T5.5 10v4q0 .074.014.146q.015.073.043.141t.069.13t.094.113q.052.053.113.094t.13.069t.141.043t.146.014t.146-.014q.073-.015.141-.043t.13-.069q.061-.041.113-.094q.053-.052.094-.113t.069-.13t.043-.141T7 14");
}

</style>
