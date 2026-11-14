<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y-dsjbblp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:laundry-detergent" /></template>
<style>
.y-dsjbblp {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M11.25 2.25h-2.5q-2.5 0-2.5 2.5v.5q0 .581.135 1.028Q3.25 6.571 3.25 10v11q0 .074.014.146q.015.073.043.141t.069.13q.041.061.094.113q.052.053.113.094t.13.069t.141.043t.146.014h12q.074 0 .146-.014q.073-.015.141-.043t.13-.069q.061-.041.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146v-4.25H18q3.25 0 3.25-3.25v-2q0-3.25-3.25-3.25h-1.523q-.652-1.765-2.862-1.972q.135-.447.135-1.028v-.5q0-2.5-2.5-2.5m5.496 7.5H18q1.75 0 1.75 1.75v2q0 1.75-1.75 1.75h-1.25V10q0-.127-.004-.25m-7.322.77q.043-.053.096-.096q.057-.047.121-.083q.065-.035.136-.057q.07-.022.144-.03t.147-.001t.144.028t.137.055q.065.034.122.081q.058.046.105.103q2.674 3.208 2.674 4.98q0 3.25-3.25 3.25T6.75 15.5q0-1.772 2.674-4.98");
}

</style>
