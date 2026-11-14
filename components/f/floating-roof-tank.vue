<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zd7vm6bvm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:floating-roof-tank" /></template>
<style>
.zd7vm6bvm {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M4.75 12.25V3.5q0-.074-.014-.146q-.015-.073-.043-.141t-.069-.13t-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043Q4.074 2.75 4 2.75t-.146.014t-.141.043t-.13.069t-.113.094q-.053.052-.094.113t-.069.13t-.043.141q-.014.072-.014.146v15q0 2.75 2.75 2.75h12q2.75 0 2.75-2.75v-15q0-.074-.014-.146q-.015-.073-.043-.141t-.069-.13t-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043T20 2.75t-.146.014q-.073.015-.141.043t-.13.069q-.061.041-.113.094q-.053.052-.094.113t-.069.13t-.043.141t-.014.146v8.75h-1.588q.088-.294.088-.625q0-2.125-2.125-2.125h-7.25q-2.125 0-2.125 2.125q0 .331.088.625zm10.875 1.5h3.625v4.75q0 1.25-1.25 1.25H6q-1.25 0-1.25-1.25v-4.75z");
}

</style>
