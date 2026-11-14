<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y90mtsbtd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:jiu-jitsu-gi" /></template>
<style>
.y90mtsbtd {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M11.625 4.25h.75q2.598 0 3.196 2H21.5q.074 0 .146.014q.073.015.141.043t.13.069q.061.041.113.094q.053.052.094.113t.069.13t.043.141t.014.146v4q0 .074-.014.146q-.015.073-.043.141t-.069.13t-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014h-5.929q-.144.481-.404.847q.677.459.894 1.27l1.035 3.863q.583 2.172-1.59 2.755t-2.755-1.59L12 16.096l-.751 2.799q-.583 2.173-2.755 1.59q-2.173-.583-1.59-2.755l1.035-3.863q.217-.811.894-1.27q-.26-.366-.404-.847H2.5q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141Q1.75 11.074 1.75 11V7q0-.074.014-.146q.015-.073.043-.141t.069-.13q.041-.061.094-.113q.052-.053.113-.094t.13-.069t.141-.043t.146-.014h5.929q.598-2 3.196-2M8.25 7.75h-5v2.5h5zm7.5 2.5h5v-2.5h-5z");
}

</style>
