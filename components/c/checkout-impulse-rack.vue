<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a29gstfxx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:checkout-impulse-rack" /></template>
<style>
.a29gstfxx {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M6.625 1.75h10.75q3.375 0 3.375 3.375v9.75q0 2.905-2.5 3.309V21.5q0 .074-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069q-.061-.041-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141t-.014-.146v-3.25h-9.5v3.25q0 .074-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014t-.146-.014q-.073-.015-.141-.043t-.13-.069q-.061-.041-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141t-.014-.146v-3.316q-2.5-.404-2.5-3.309v-9.75q0-3.375 3.375-3.375M11.25 7q0-2.25-2.25-2.25T6.75 7v6q0 2.25 2.25 2.25T11.25 13zM15 4.75q-2.25 0-2.25 2.25v6q0 2.25 2.25 2.25T17.25 13V7q0-2.25-2.25-2.25");
}

</style>
