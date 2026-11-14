<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f5xi2xbtq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:business-trip" /></template>
<style>
.f5xi2xbtq {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M17.505 7.495q-.971-.971-2.255-1.185V2.5q0-.074-.014-.146q-.015-.073-.043-.141t-.069-.13t-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043q-.072-.014-.146-.014h-5q-.074 0-.146.014q-.073.015-.141.043t-.13.069t-.113.094q-.053.052-.094.113t-.069.13t-.043.141t-.014.146v3.81q-1.284.214-2.255 1.185Q5.25 8.74 5.25 10.5V16q0 1.76 1.245 3.005q.411.412.879.687q-.124.342-.124.808q0 1.75 1.75 1.75t1.75-1.75q0-.13-.01-.25h2.52q-.01.12-.01.25q0 1.75 1.75 1.75t1.75-1.75q0-.466-.124-.808q.468-.275.879-.687Q18.75 17.76 18.75 16v-5.5q0-1.76-1.245-3.005M13.75 6.25h-3.5v-3h3.5z");
}

</style>
