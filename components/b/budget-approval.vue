<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="czxpvk-er"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:budget-approval" /></template>
<style>
.czxpvk-er {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M13.75 1.75h-3.5q-1.937 0-2.373 1.502q-1.681.042-2.882 1.243Q3.75 5.74 3.75 7.5V18q0 1.76 1.245 3.005T8 22.25h8q1.76 0 3.005-1.245T20.25 18V7.5q0-1.76-1.245-3.005q-1.227-1.227-2.955-1.245q-.183-.418-.532-.768q-.732-.732-1.768-.732M11 14.939l3.97-3.969q.052-.053.113-.094t.13-.069t.141-.043t.146-.014t.146.014q.073.015.141.043t.13.069t.113.094q.106.105.163.243t.057.287t-.057.287t-.163.243l-4.5 4.5q-.052.053-.113.094t-.13.069t-.141.043t-.146.014t-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094l-2.5-2.5q-.106-.105-.163-.243T7.75 13.5t.057-.287t.163-.243q.052-.053.113-.094t.13-.069t.141-.043t.146-.014t.146.014q.073.015.141.043t.13.069t.113.094z");
}

</style>
