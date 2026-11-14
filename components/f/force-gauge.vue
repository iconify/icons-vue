<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iotpyjomi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:force-gauge" /></template>
<style>
.iotpyjomi {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M6.52 4.02Q4.25 6.29 4.25 9.5t2.27 5.48q2 2 4.73 2.238v1.532q0 1.5-1.5 1.5t-1.5-1.5q0-.074-.014-.146q-.015-.073-.043-.141t-.069-.13q-.041-.061-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043T7.5 18t-.146.014q-.073.015-.141.043t-.13.069q-.061.041-.113.094q-.053.052-.094.113t-.069.13t-.043.141t-.014.146q0 3 3 3t3-3v-1.532q2.73-.238 4.73-2.238q2.27-2.27 2.27-5.48t-2.27-5.48T12 1.75T6.52 4.02m4.95 4.949l2.75-2.749q.105-.106.243-.163T14.75 6t.287.057t.243.163q.053.052.094.113t.069.13t.043.141t.014.146t-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113l-2.672 2.673q-.052.069-.119.124q-.067.056-.145.095q-.078.038-.162.058q-.085.02-.172.02H12q-.149 0-.287-.057t-.243-.163q-.106-.105-.163-.243T11.25 9.5t.057-.287t.163-.243z");
}

</style>
