<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v--s36aks"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:golf-rangefinder" /></template>
<style>
.v--s36aks {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M2.5 8.75h3.689L8.97 5.97q.105-.106.243-.163T9.5 5.75h10q2.75 0 2.75 2.75v7q0 2.75-2.75 2.75h-10q-.149 0-.287-.057t-.243-.163l-2.781-2.78H2.5q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141q-.014-.072-.014-.146v-5q0-.074.014-.146q.015-.073.043-.141t.069-.13t.094-.113q.052-.053.113-.094t.13-.069t.141-.043t.146-.014m13 0q-3.25 0-3.25 3.25t3.25 3.25T18.75 12T15.5 8.75");
}

</style>
