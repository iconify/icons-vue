<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dna1wgiku"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:fertiliser-granules" /></template>
<style>
.dna1wgiku {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M5.25 9.75q0 1.243.878 2.122q.879.879 2.122.879t2.122-.879t.878-2.122q.001-1.243-.878-2.122T8.25 6.749t-2.122.879T5.25 9.75m10.5 3q-3 0-3-3t3-3t3 3t-3 3m.892 4.75q-.392-.668-.392-1.499v-.002q0-1.242.878-2.121q.879-.88 2.122-.88t2.122.88q.879.879.878 2.121q.001.876-.435 1.571q.098.045.178.115q.081.071.139.161t.088.194t.03.21q0 .074-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043T21.5 19h-2.146l-.104.002l-.104-.002H2.5q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141t-.014-.146q0-.09.021-.178t.063-.168t.101-.148q.06-.068.134-.119Q1.75 16.978 1.75 16q0-3 3-3t3 3q0 .879-.257 1.5h1.764Q9 16.879 9 16q0-3 3-3t3 3q0 .879-.257 1.5z");
}

</style>
