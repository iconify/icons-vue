<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x65_0vbke"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:dirndl-style-dress" /></template>
<style>
.x65_0vbke {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M8 2.25h2q.149 0 .287.057t.243.163q1.47 1.469 2.94 0q.105-.106.243-.163T14 2.25h2q.074 0 .146.014q.073.015.141.043t.13.069q.061.041.113.094q.053.052.094.113t.069.13t.043.141t.014.146q0 .05-.007.099l-.931 6.983q5.103 2.861 5.933 10.335q.009.074.002.147q-.006.074-.027.145t-.054.136q-.034.066-.08.124t-.103.105t-.121.083t-.135.058t-.144.03q-.041.005-.083.005H3q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141t-.014-.146q0-.042.005-.083q.83-7.474 5.933-10.335l-.931-6.983q-.01-.073-.005-.147q.004-.074.023-.145t.052-.138t.077-.125t.101-.107q.055-.049.119-.086t.134-.061t.143-.033Q7.95 2.25 8 2.25");
}

</style>
