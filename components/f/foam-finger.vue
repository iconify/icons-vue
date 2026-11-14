<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ekbaddcid"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:foam-finger" /></template>
<style>
.ekbaddcid {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M7.5 9.25h.25V5q0-3.25 3.25-3.25T14.25 5v4.25h2.25q3.25 0 3.25 3.25V15q0 2.7-2.243 3.157q.243.496.243 1.093v.5q0 1.036-.732 1.768t-1.768.732h-6.5q-1.036 0-1.768-.732T6.25 19.75v-.5q0-.597.243-1.093Q4.25 17.7 4.25 15v-2.5q0-1.346.952-2.298T7.5 9.25M14.25 14v-4q0-.074-.014-.146q-.015-.073-.043-.141t-.069-.13t-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043t-.146-.014t-.146.014q-.073.015-.141.043t-.13.069t-.113.094q-.053.052-.094.113t-.069.13t-.043.141t-.014.146v4q0 .074.014.146q.015.073.043.141t.069.13t.094.113q.052.053.113.094t.13.069t.141.043t.146.014t.146-.014q.073-.015.141-.043t.13-.069t.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146");
}

</style>
