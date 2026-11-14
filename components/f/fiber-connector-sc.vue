<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xcji33ckr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:fiber-connector-sc" /></template>
<style>
.xcji33ckr {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M10.625 6.25h3.75q3.375 0 3.375 3.375v.201q.337-.076.75-.076h1q2.25 0 2.25 2.25t-2.25 2.25h-1q-.413 0-.75-.076v.201q0 3.375-3.375 3.375h-3.75q-3.375 0-3.375-3.375V12.75H2.5q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141Q1.75 12.074 1.75 12t.014-.146q.015-.073.043-.141t.069-.13t.094-.113q.052-.053.113-.094t.13-.069t.141-.043t.146-.014h4.75V9.625q0-3.375 3.375-3.375");
}

</style>
