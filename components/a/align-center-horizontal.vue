<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b394x3bnc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:align-center-horizontal" /></template>
<style>
.b394x3bnc {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M7.625 2.75h.25q3.375 0 3.375 3.375v5.125h1.5V9.625q0-3.375 3.375-3.375h.25q3.375 0 3.375 3.375v1.625h1.75q.074 0 .146.014q.073.015.141.043t.13.069q.061.041.113.094q.053.052.094.113t.069.13t.043.141t.014.146t-.014.146q-.015.073-.043.141t-.069.13t-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014h-1.75v1.625q0 3.375-3.375 3.375h-.25q-3.375 0-3.375-3.375V12.75h-1.5v5.125q0 3.375-3.375 3.375h-.25q-3.375 0-3.375-3.375V12.75H2.5q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141Q1.75 12.074 1.75 12t.014-.146q.015-.073.043-.141t.069-.13t.094-.113q.052-.053.113-.094t.13-.069t.141-.043t.146-.014h1.75V6.125q0-3.375 3.375-3.375");
}

</style>
