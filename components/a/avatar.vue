<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xj22cxy2o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:avatar" /></template>
<style>
.xj22cxy2o {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M8.288 3.788Q6.75 5.325 6.75 7.5t1.538 3.712Q9.825 12.75 12 12.75t3.712-1.538Q17.25 9.675 17.25 7.5t-1.538-3.712Q14.175 2.25 12 2.25T8.288 3.788M3.25 21q0-6.75 8.75-6.75T20.75 21q0 .074-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014t-.146-.014q-.073-.015-.141-.043t-.13-.069q-.061-.041-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141T19.25 21q0-5.25-7.25-5.25T4.75 21q0 .074-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043T4 21.75t-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141T3.25 21");
}

</style>
