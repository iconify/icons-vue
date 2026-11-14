<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lzs6mobbr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:boat-front-view" /></template>
<style>
.lzs6mobbr {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M20.5 12.25h-1.582l-6.28-10.145q-.093-.15-.243-.243q-.182-.112-.395-.112h-.009q-.082.001-.163.02q-.145.034-.266.121t-.2.214L5.082 12.25H3.5q-.074 0-.146.014q-.073.015-.141.043t-.13.069t-.113.094q-.053.052-.094.113t-.069.13t-.043.141q-.014.072-.014.146q0 4.028 2.618 6.428Q7.901 21.75 12 21.75t6.632-2.322q2.618-2.4 2.618-6.428q0-.074-.014-.146q-.015-.073-.043-.141t-.069-.13t-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043t-.146-.014m-9.25-7.114L6.846 12.25h4.404zm1.5 7.114V5.136l4.404 7.114z");
}

</style>
