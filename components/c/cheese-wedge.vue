<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e949h0bcj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:cheese-wedge" /></template>
<style>
.e949h0bcj {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M3.5 17.75q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141T2.75 17V7q0-.087.02-.172q.017-.072.047-.139q.031-.067.074-.127t.097-.11t.117-.09t.132-.064q.069-.026.142-.038t.147-.01t.146.02l17 4q.061.014.119.039q.058.024.111.058t.1.076t.086.091t.069.105q.031.055.051.114q.021.06.032.122t.01.125v6q0 .074-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014zm4.5-7q-2.25 0-2.25 2.25T8 15.25T10.25 13T8 10.75m5 2.75q0 2 2 2t2-2t-2-2t-2 2");
}

</style>
