<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qj1_r9s4w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:cause-carers" /></template>
<style>
.qj1_r9s4w {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("m8.72 18.78l-5.5-5.5q-.042-.041-.077-.089q-1.425-1.96-1.047-4.353q.378-2.394 2.338-3.82t4.353-1.047q1.917.303 3.213 1.62q1.296-1.316 3.212-1.618q2.393-.377 4.353 1.047q1.959 1.425 2.337 3.818t-1.045 4.353q-.035.048-.077.089l-5.5 5.5q.106-.105.163-.243t.057-.287q0-2.75-3.5-2.75t-3.5 2.75q0 .149.057.287t.163.243m0 0q.105.106.243.163T9.25 19q.074 0 .146-.014q.073-.015.141-.043t.13-.069t.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146Q10 17 12 17t2 1.25q0 .074.014.146q.015.073.043.141t.069.13q.041.061.094.113q.052.053.113.094t.13.069t.141.043t.146.014q.149 0 .287-.057t.243-.163l-2.75 2.75q-.052.053-.113.094t-.13.069t-.141.043t-.146.014t-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094zM15 11.25q0-3-3-3t-3 3t3 3t3-3");
}

</style>
