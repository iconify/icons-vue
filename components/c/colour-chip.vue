<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="upc_k2b3b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:colour-chip" /></template>
<style>
.upc_k2b3b {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M19 2.25H5Q2.25 2.25 2.25 5v14q0 2.75 2.75 2.75h10q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141T14.25 21v-4q0-2.75 2.75-2.75h4q.074 0 .146.014q.073.015.141.043t.13.069q.061.041.113.094q.053.052.094.113t.069.13t.043.141t.014.146V5q0-2.75-2.75-2.75m2.53 13.28q-.105.106-.243.163T21 15.75h-4q-1.25 0-1.25 1.25v4q0 .149-.057.287t-.163.243z");
}

</style>
