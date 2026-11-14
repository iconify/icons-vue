<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d7oz6gflw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:dish-soap" /></template>
<style>
.d7oz6gflw {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M17 2.75H9.5q-.074 0-.146.014q-.073.015-.141.043t-.13.069t-.113.094q-.053.052-.094.113t-.069.13t-.043.141t-.014.146t.014.146q.015.073.043.141t.069.13t.094.113q.052.053.113.094t.13.069t.141.043t.146.014h1.75v4H8q-2.75 0-2.75 2.75v8.5q0 2.75 2.75 2.75h8q2.75 0 2.75-2.75V11q0-2.75-2.75-2.75h-3.25v-4h3.5V5.5q0 .074.014.146q.015.073.043.141t.069.13q.041.061.094.113q.052.053.113.094t.13.069t.141.043t.146.014q.074 0 .146-.014q.073-.015.141-.043t.13-.069q.061-.041.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146v-2q0-.074-.014-.146q-.015-.073-.043-.141t-.069-.13t-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043T17 2.75m-8.25 12.5Q8.75 12 12 12t3.25 3.25T12 18.5t-3.25-3.25");
}

</style>
