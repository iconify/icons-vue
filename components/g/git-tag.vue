<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gr2t7fbuc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:git-tag" /></template>
<style>
.gr2t7fbuc {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M10.967 4.75h6.908q3.375 0 3.375 3.375v7.75q0 3.375-3.375 3.375h-6.908q-1.886 0-2.875-1.606l-2.384-3.875q-.313-.509-.446-1.019H2.5q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141Q1.75 12.074 1.75 12t.014-.146t.043-.141t.069-.13t.094-.113q.052-.053.113-.094t.13-.069t.141-.043t.146-.014h2.762q.133-.51.446-1.019l2.384-3.875q.989-1.606 2.875-1.606m.033 5q-2.25 0-2.25 2.25T11 14.25q.932 0 1.591-.659T13.25 12t-.659-1.591T11 9.75");
}

</style>
