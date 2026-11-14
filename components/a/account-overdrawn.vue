<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lg_nhw5zt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:account-overdrawn" /></template>
<style>
.lg_nhw5zt {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M1.25 12q0-3.831 2.709-6.541Q6.669 2.75 10.5 2.75h3q3.831.001 6.539 2.71T22.747 12t-2.708 6.54t-6.539 2.71h-3q-3.831 0-6.541-2.709Q1.25 15.831 1.25 12m14.964 7.284q1.523-.563 2.764-1.805q2.269-2.27 2.269-5.479t-2.269-5.479q-1.241-1.242-2.764-1.805q.426.342.827.743Q19.75 8.169 19.75 12t-2.709 6.541q-.401.401-.827.743M14.75 12q0-.074-.014-.146q-.015-.073-.043-.141t-.069-.13t-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043T14 11.25H7q-.074 0-.146.014q-.073.015-.141.043t-.13.069q-.061.041-.113.094q-.053.052-.094.113t-.069.13t-.043.141T6.25 12t.014.146q.015.073.043.141t.069.13t.094.113q.052.053.113.094t.13.069t.141.043t.146.014h7q.074 0 .146-.014q.073-.015.141-.043t.13-.069t.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146");
}

</style>
