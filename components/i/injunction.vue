<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n34v1jbce"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:injunction" /></template>
<style>
.n34v1jbce {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M15.025 2.5h-6.05q-1.036 0-1.768.733L3.233 7.206Q2.5 7.939 2.5 8.975v6.05q0 1.036.733 1.768l3.973 3.974q.733.733 1.769.733h6.05q1.036 0 1.768-.733l3.974-3.973q.733-.733.733-1.769v-6.05q0-1.036-.733-1.768l-3.973-3.974q-.733-.733-1.769-.733m1.475 8.75q.074 0 .146.014q.073.015.141.043t.13.069q.061.041.113.094q.053.052.094.113t.069.13t.043.141t.014.146t-.014.146q-.015.073-.043.141t-.069.13t-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014h-9q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069q-.061-.041-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141T6.75 12t.014-.146q.015-.073.043-.141t.069-.13t.094-.113q.052-.053.113-.094t.13-.069t.141-.043t.146-.014z");
}

</style>
