<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="id6rsqukl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:landing-gear" /></template>
<style>
.id6rsqukl {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M21.5 2.75h-19q-.074 0-.146.014q-.073.015-.141.043t-.13.069t-.113.094q-.053.052-.094.113t-.069.13t-.043.141q-.014.072-.014.146V5q0 3.75 3.75 3.75h1.715l4.035 3.587v.467q-1.491.219-2.609 1.337Q7.25 15.532 7.25 17.5t1.391 3.359T12 22.25t3.359-1.391T16.75 17.5t-1.391-3.359q-1.118-1.118-2.609-1.337V8.75h5.75q3.75 0 3.75-3.75V3.5q0-.074-.014-.146q-.015-.073-.043-.141t-.069-.13t-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043t-.146-.014m-10.25 7.58L9.473 8.75h1.777z");
}

</style>
