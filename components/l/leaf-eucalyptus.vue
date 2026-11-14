<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m6b2v1yaw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:leaf-eucalyptus" /></template>
<style>
.m6b2v1yaw {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M8.5 5.25q0-3.5 3.5-3.5t3.5 3.5q0 3.102-2.75 3.455v.896Q13.699 9 15.25 9q4 0 4 4t-4 4q-1.551 0-2.5-.601V21.5q0 .074-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014t-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141t-.014-.146v-5.374Q10.181 17 8.75 17q-4 0-4-4t4-4q1.431 0 2.5.874V8.705Q8.5 8.352 8.5 5.25");
}

</style>
