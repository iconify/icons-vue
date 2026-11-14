<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ks67l3g2n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:binoculars-opera" /></template>
<style>
.ks67l3g2n {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M2.75 8q0-1.76 1.245-3.005T7 3.75t3.005 1.245q.971.971 1.185 2.255h1.62q.214-1.284 1.185-2.255Q15.24 3.75 17 3.75t3.005 1.245T21.25 8t-1.245 3.005T17 12.25t-3.005-1.245q-.971-.971-1.185-2.255h-.06V20.5q0 .074-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014t-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141t-.014-.146V8.75h-.06q-.214 1.284-1.185 2.255Q8.76 12.25 7 12.25t-3.005-1.245T2.75 8");
}

</style>
