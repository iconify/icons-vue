<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tyjqdibdq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:align-left" /></template>
<style>
.tyjqdibdq {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M3.75 21.5v-19q0-.074-.014-.146q-.015-.073-.043-.141t-.069-.13t-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043Q3.074 1.75 3 1.75t-.146.014t-.141.043t-.13.069t-.113.094q-.053.052-.094.113t-.069.13t-.043.141q-.014.072-.014.146v19q0 .074.014.146q.015.073.043.141t.069.13q.041.061.094.113q.052.053.113.094t.13.069t.141.043t.146.014t.146-.014q.073-.015.141-.043t.13-.069t.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146M8.625 3.75h8.25q3.375 0 3.375 3.375v.25q0 3.375-3.375 3.375h-8.25q-3.375 0-3.375-3.375v-.25q0-3.375 3.375-3.375m3.25 9.5h-3.25q-1.398 0-2.386.989q-.989.988-.989 2.386v.25q0 3.375 3.375 3.375h3.25q3.375 0 3.375-3.375v-.25q0-3.375-3.375-3.375");
}

</style>
