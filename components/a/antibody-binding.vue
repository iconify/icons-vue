<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u2gnibejz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:antibody-binding" /></template>
<style>
.u2gnibejz {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M7.805 5.281q.207-1.304 1.19-2.286Q10.24 1.75 12 1.75t3.005 1.245q.983.982 1.19 2.286q1.554.147 2.256.989q.893 1.071.261 2.967q-.056.168-.182.293l-5.78 5.781V21.5q0 .074-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014t-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141t-.014-.146v-6.189L5.47 9.53q-.126-.125-.182-.293q-.632-1.896.261-2.967q.702-.842 2.256-.989m.011 1.504q-.823.095-1.115.445q-.33.397-.041 1.369l5.34 5.34l5.34-5.34q.289-.972-.041-1.369q-.292-.35-1.115-.445q-.221 1.263-1.179 2.22Q13.76 10.25 12 10.25T8.995 9.005q-.958-.957-1.179-2.22");
}

</style>
