<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gks_vy-4w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:halving" /></template>
<style>
.gks_vy-4w {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M10.5 2.75q-3.831.001-6.539 2.71T1.253 12t2.708 6.54t6.539 2.71q.074 0 .146-.014q.073-.015.141-.043t.129-.069t.114-.093q.052-.053.093-.114q.042-.062.07-.13t.043-.14t.014-.147v-17q0-.074-.014-.146q-.015-.073-.043-.141t-.069-.13t-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043q-.072-.014-.146-.014m3 0q3.831.001 6.539 2.71T22.747 12t-2.708 6.54t-6.539 2.71q-.074 0-.146-.014q-.073-.015-.141-.043t-.129-.069t-.114-.093q-.052-.053-.093-.114q-.042-.062-.07-.13t-.043-.14t-.014-.147v-17q0-.074.014-.146q.015-.073.043-.141t.069-.13t.094-.113q.052-.053.113-.094t.13-.069t.141-.043q.072-.014.146-.014");
}

</style>
