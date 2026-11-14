<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jvkrelbfv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:billing-address" /></template>
<style>
.jvkrelbfv {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M6.75 1.75h10.5q2.5 0 2.5 2.5v15.5q0 1.036-.732 1.768t-1.768.732H6.75q-1.036 0-1.768-.732T4.25 19.75V4.25q0-2.5 2.5-2.5M14.5 17H8q-.074 0-.146.014q-.073.015-.141.043t-.13.069q-.061.041-.113.094q-.053.052-.094.113t-.069.13t-.043.141t-.014.146q0 .074.014.146q.015.073.043.141t.069.13q.041.061.094.113q.052.053.113.094t.13.069t.141.043T8 18.5h6.5q.074 0 .146-.014q.073-.015.141-.043t.13-.069t.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146t-.014-.146q-.015-.073-.043-.141t-.069-.13q-.041-.061-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043T14.5 17");
}

</style>
