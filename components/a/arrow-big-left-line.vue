<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hct1l1x2s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:arrow-big-left-line" /></template>
<style>
.hct1l1x2s {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("m4.017 9.923l4.039-4.039q.745-.747 1.72-.343t.974 1.46q0 1.249 1.25 1.249h1.813q2.937.001 2.937 2.938v1.625q-.001 2.936-2.937 2.937H12q-1.25 0-1.25 1.25q.001 1.055-.974 1.459t-1.721-.343l-4.038-4.039Q1.94 12 4.017 9.923M19.75 9v6q0 .074.014.146q.015.073.043.141t.069.13t.094.113q.052.053.113.094t.13.069t.141.043t.146.014t.146-.014q.073-.015.141-.043t.13-.069q.061-.041.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146V9q0-.074-.014-.146q-.015-.073-.043-.141t-.069-.13t-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043t-.146-.014t-.146.014q-.073.015-.141.043t-.13.069q-.061.041-.113.094q-.053.052-.094.113t-.069.13t-.043.141T19.75 9");
}

</style>
