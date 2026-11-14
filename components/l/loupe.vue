<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="giopicbmq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:loupe" /></template>
<style>
.giopicbmq {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M2.25 10q0-3.21 2.27-5.48T10 2.25t5.48 2.27T17.75 10q0 2.075-.949 3.758q.649.157 1.154.662l1.414 1.414q.733.732.733 1.768q0 1.035-.733 1.767q-.732.733-1.767.733q-1.036 0-1.768-.733l-1.414-1.414q-.505-.505-.662-1.154q-1.683.949-3.758.949q-3.21 0-5.48-2.27T2.25 10m4.391-3.359Q5.25 8.032 5.25 10q0 .074.014.146q.015.073.043.141t.069.13t.094.113q.052.053.113.094t.13.069t.141.043t.146.014t.146-.014q.073-.015.141-.043t.13-.069q.061-.041.113-.094q.053-.052.094-.113t.069-.13t.043-.141T6.75 10q0-3.25 3.25-3.25q.074 0 .146-.014q.073-.015.141-.043t.13-.069t.113-.094q.053-.052.094-.113t.069-.13t.043-.141T10.75 6t-.014-.146q-.015-.073-.043-.141t-.069-.13q-.041-.061-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043T10 5.25q-1.968 0-3.359 1.391");
}

</style>
