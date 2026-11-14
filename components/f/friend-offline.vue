<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ijr7i7dpf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:friend-offline" /></template>
<style>
.ijr7i7dpf {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M6.964 3.964Q5.5 5.429 5.5 7.5t1.464 3.536T10.5 12.5t3.536-1.464Q15.5 9.571 15.5 7.5t-1.464-3.536Q12.571 2.5 10.5 2.5T6.964 3.964m7.927 10.927q-.446.447-.75.953q-1.472-.594-3.641-.594q-6.75 0-6.75 5.75q0 .074-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043T3 21.75t-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141T2.25 21q0-3.295 2.425-5.325Q6.974 13.75 10.5 13.75q2.581 0 4.504 1.031q-.057.054-.113.11m-.141 3.359q0-3.5 3.5-3.5t3.5 3.5t-3.5 3.5t-3.5-3.5m1.5 0q0 2 2 2t2-2t-2-2t-2 2m2.24.727q-.209-.756-.584-1.425q-.406.146-.406.698q0 .75.75.75q.131 0 .24-.023");
}

</style>
