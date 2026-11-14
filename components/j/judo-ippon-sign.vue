<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b661g3ujz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:judo-ippon-sign" /></template>
<style>
.b661g3ujz {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M8.5 1.75h7q1.76 0 3.005 1.245T19.75 6v7q0 1.76-1.245 3.005T15.5 17.25h-2.75v4.25q0 .074-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014t-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141t-.014-.146v-4.25H8.5q-1.76 0-3.005-1.245T4.25 13V6q0-1.76 1.245-3.005T8.5 1.75M7.75 9.5q0 1.76 1.245 3.005T12 13.75t3.005-1.245T16.25 9.5t-1.245-3.005T12 5.25T8.995 6.495T7.75 9.5");
}

</style>
