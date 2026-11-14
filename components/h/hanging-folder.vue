<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a3t8gbcyg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:hanging-folder" /></template>
<style>
.a3t8gbcyg {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M17.5 2.75h-15q-.074 0-.146.014q-.073.015-.141.043t-.13.069t-.113.094q-.053.052-.094.113t-.069.13t-.043.141q-.014.072-.014.146t.014.146t.043.141t.069.13t.094.113q.052.053.113.094t.13.069t.141.043t.146.014h3.25v4H5q-2.75 0-2.75 2.75v8q0 2.75 2.75 2.75h14q2.75 0 2.75-2.75v-6q0-2.75-2.75-2.75h-.75v-6h3.25q.074 0 .146-.014q.073-.015.141-.043t.13-.069q.061-.041.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146t-.014-.146q-.015-.073-.043-.141t-.069-.13t-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043t-.146-.014zm-.75 1.5h-9.5v4H9.5q.149 0 .287.057t.243.163l1.781 1.78h4.939z");
}

</style>
