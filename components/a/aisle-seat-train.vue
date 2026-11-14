<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sog9d3bfu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:aisle-seat-train" /></template>
<style>
.sog9d3bfu {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M9.375 1.75h5.25q2.625 0 2.625 2.625q0 1.087-.769 1.856T14.625 7h-5.25q-1.087 0-1.856-.769T6.75 4.375t.769-1.856t1.856-.769M5.75 11v3.278q-2 .236-2 2.472q0 1.036.732 1.768t1.768.732v2.25q0 .074.014.146q.015.073.043.141t.069.13q.041.061.094.113q.052.053.113.094t.13.069t.141.043t.146.014t.146-.014q.073-.015.141-.043t.13-.069q.061-.041.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146v-2.25h8.5v2.25q0 .074.014.146q.015.073.043.141t.069.13q.041.061.094.113q.052.053.113.094t.13.069t.141.043t.146.014q.074 0 .146-.014q.073-.015.141-.043t.13-.069q.061-.041.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146v-2.25q1.036 0 1.768-.732t.732-1.768q0-2.236-2-2.472V11q0-2.75-2.75-2.75h-7q-2.75 0-2.75 2.75m1.5 3.25V11q0-1.25 1.25-1.25h7q1.25 0 1.25 1.25v3.25z");
}

</style>
