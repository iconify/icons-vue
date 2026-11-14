<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="up3892b7g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:coracle" /></template>
<style>
.up3892b7g {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M19.25 13.326q-1.5.337-1.5 2.174V20q0 2.25 2.25 2.25T22.25 20v-4.5q0-1.837-1.5-2.174V2.5q0-.074-.014-.146q-.015-.073-.043-.141t-.069-.13t-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043T20 1.75t-.146.014q-.073.015-.141.043t-.13.069q-.061.041-.113.094q-.053.052-.094.113t-.069.13t-.043.141t-.014.146zM2.5 10.75H16q.074 0 .146.014q.073.015.141.043t.13.069q.061.041.113.094q.053.052.094.113t.069.13t.043.141t.014.146q0 3.107-2.197 5.303Q12.357 19 9.25 19t-5.303-2.197T1.75 11.5q0-.074.014-.146q.015-.073.043-.141t.069-.13t.094-.113q.052-.053.113-.094t.13-.069t.141-.043t.146-.014");
}

</style>
