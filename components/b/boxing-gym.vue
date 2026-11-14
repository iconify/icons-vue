<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sswh8vbbe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:boxing-gym" /></template>
<style>
.sswh8vbbe {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M5.25 5.75V4q0-.074-.014-.146q-.015-.073-.043-.141t-.069-.13t-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043Q4.574 3.25 4.5 3.25t-.146.014t-.141.043t-.13.069t-.113.094q-.053.052-.094.113t-.069.13t-.043.141Q3.75 3.926 3.75 4v10.778q-2 .236-2 2.472v1.5q0 2.5 2.5 2.5h15.5q1.036 0 1.768-.732t.732-1.768v-1.5q0-1.036-.732-1.768q-.549-.548-1.268-.686V4q0-.074-.014-.146q-.015-.073-.043-.141t-.069-.13t-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043t-.146-.014t-.146.014q-.073.015-.141.043t-.13.069q-.061.041-.113.094q-.053.052-.094.113t-.069.13t-.043.141T18.75 4v1.75zm13.5 6H5.25v-1.5h13.5zm-13.5 1.5h13.5v1.5H5.25zm0-4.5v-1.5h13.5v1.5z");
}

</style>
