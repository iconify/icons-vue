<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gy98uob4e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:chemical-spill" /></template>
<style>
.gy98uob4e {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M10.875 3.25h-5.75q-3.375 0-3.375 3.375v1.75q0 1.398.989 2.386q.988.989 2.386.989h5.75q1.398 0 2.386-.989q.462-.461.708-1.011H16q.074 0 .146-.014q.073-.015.141-.043t.13-.069q.061-.041.113-.094q.053-.052.094-.113t.069-.13t.043-.141T16.75 9v-.316q1.339 1.259 1.483 5.904q-1.912-.338-4.733-.338q-8.75 0-8.75 3.25q0 .394.129.74q.932 2.51 8.621 2.51q8.75 0 8.75-3.25q0-1.74-2.509-2.549q-.152-6.891-2.991-8.018V6q0-.074-.014-.146q-.015-.073-.043-.141t-.069-.13q-.041-.061-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043T16 5.25h-1.929q-.598-2-3.196-2m4.375 3.5v1.5h-1v-1.5z");
}

</style>
