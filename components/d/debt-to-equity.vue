<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="twaod2b0z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:debt-to-equity" /></template>
<style>
.twaod2b0z {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M15.25 1.75h-6.5q-2.5 0-2.5 2.5v5H4q-.074 0-.146.014q-.073.015-.141.043t-.13.069t-.113.094q-.053.052-.094.113t-.069.13t-.043.141q-.014.072-.014.146t.014.146q.015.073.043.141t.069.13t.094.113q.052.053.113.094t.13.069t.141.043t.146.014h2.25v9q0 1.036.732 1.768t1.768.732h6.5q1.036 0 1.768-.732t.732-1.768v-9H20q.074 0 .146-.014q.073-.015.141-.043t.13-.069q.061-.041.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146t-.014-.146q-.015-.073-.043-.141t-.069-.13t-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043T20 9.25h-2.25v-5q0-2.5-2.5-2.5");
}

</style>
