<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ryjvj5k1b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:jib-sail" /></template>
<style>
.ryjvj5k1b {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M6.75 21.5v-19q0-.074-.014-.146q-.015-.073-.043-.141t-.069-.13t-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043Q6.074 1.75 6 1.75t-.146.014t-.141.043t-.13.069t-.113.094q-.053.052-.094.113t-.069.13t-.043.141t-.014.146v19q0 .074.014.146q.015.073.043.141t.069.13q.041.061.094.113q.052.053.113.094t.13.069t.141.043t.146.014t.146-.014q.073-.015.141-.043t.13-.069q.061-.041.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146m5.651-13.032l5.275 8.328q.712 1.123.07 2.289t-1.973 1.165H10.5q-2.25 0-2.25-2.25V9.672q0-1.69 1.623-2.161t2.527.957z");
}

</style>
