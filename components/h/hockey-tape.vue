<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rfdnpccnj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:hockey-tape" /></template>
<style>
.rfdnpccnj {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M3.75 10.5q0-3.417 2.416-5.834T12 2.25t5.834 2.416Q20.25 7.083 20.25 10.5t-2.416 5.834T12 18.75t-5.834-2.416q-.512-.513-.916-1.07V21q0 .074-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014t-.146-.014q-.073-.015-.141-.043t-.13-.069q-.061-.041-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141T3.75 21zM12 6.75q-3.75 0-3.75 3.75T12 14.25t3.75-3.75T12 6.75");
}

</style>
