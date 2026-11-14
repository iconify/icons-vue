<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z_fun4est"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:currency-rand" /></template>
<style>
.z_fun4est {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M7.25 4.5v15q0 .074.014.146q.015.073.043.141t.069.13q.041.061.094.113q.052.053.113.094t.13.069t.141.043t.146.014t.146-.014q.073-.015.141-.043t.13-.069t.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146v-6.25h3.578l4.031 6.639q.038.063.088.118t.11.098q.059.044.126.075t.139.049q.072.017.145.02q.074.003.147-.008t.143-.036q.069-.026.132-.064t.118-.088t.098-.11t.075-.126t.049-.139t.02-.145q.003-.074-.008-.147t-.036-.143q-.026-.069-.064-.132l-3.597-5.926q3.706-.489 3.706-4.685q0-4.75-4.75-4.75H8q-.074 0-.146.014q-.073.015-.141.043t-.13.069q-.061.041-.113.094q-.053.052-.094.113t-.069.13t-.043.141t-.014.146M13 11.75H8.75v-6.5H13q3.25 0 3.25 3.25T13 11.75");
}

</style>
