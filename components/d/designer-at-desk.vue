<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zm95a-blk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:designer-at-desk" /></template>
<style>
.zm95a-blk {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M3.25 9q0-3.25 3.25-3.25T9.75 9T6.5 12.25T3.25 9m11.375-1.75h4.25q3.375 0 3.375 3.375v2.25q0 3.375-3.375 3.375H17.5v1.5h4q.074 0 .146.014q.073.015.141.043t.13.069q.061.041.113.094q.053.052.094.113t.069.13t.043.141t.014.146q0 .074-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014h-19q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141t-.014-.146q0-1.968 1.391-3.359T6.5 13.75t3.359 1.391q1.118 1.118 1.337 2.609H16v-1.5h-1.375q-3.375 0-3.375-3.375v-2.25q0-3.375 3.375-3.375m-4.924 10.5q-.351-2.5-3.201-2.5t-3.201 2.5z");
}

</style>
