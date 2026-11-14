<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n-gatlbsq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:lozenge" /></template>
<style>
.n-gatlbsq {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M6.03 10.536q.454-1.108 1.64-1.971Q9.478 7.25 12 7.25t4.33 1.315q1.186.863 1.64 1.971l2.768-2.584q.054-.051.117-.09q.063-.038.132-.064t.142-.038t.147-.01t.146.02t.139.047q.067.031.127.074t.11.097q.098.104.15.237T22 8.5v7q0 .074-.014.146q-.015.073-.043.141t-.069.13t-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014q-.142 0-.275-.052t-.237-.15l-2.768-2.584q-.454 1.108-1.64 1.971Q14.522 16.75 12 16.75t-4.33-1.315q-1.186-.863-1.64-1.971l-2.768 2.584q-.104.098-.237.15t-.275.052q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141Q2 15.574 2 15.5v-7q0-.142.052-.275t.15-.237q.05-.054.11-.097t.127-.074t.139-.047t.146-.02q.074-.002.147.01t.142.038t.132.064q.063.039.117.09z");
}

</style>
