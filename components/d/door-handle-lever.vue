<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lj3o8obqs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:door-handle-lever" /></template>
<style>
.lj3o8obqs {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M5.625 1.75h7.25q3.375 0 3.375 3.375V8.75h3.25q2.25 0 2.25 2.25q0 .932-.659 1.591t-1.591.659h-3.25v5.625q0 3.375-3.375 3.375h-7.25q-1.398 0-2.386-.989q-.989-.988-.989-2.386V5.125q0-1.398.989-2.386q.988-.989 2.386-.989m7.125 10v-1.5H12q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141t-.014-.146t.014-.146q.015-.073.043-.141t.069-.13t.094-.113q.052-.053.113-.094t.13-.069t.141-.043T12 8.75h.75v-.5q0-1.036-.732-1.768T10.25 5.75q-2.5 0-2.5 2.5v7.5q0 2.5 2.5 2.5q1.036 0 1.768-.732t.732-1.768v-2.5H12q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141t-.014-.146t.014-.146q.015-.073.043-.141t.069-.13t.094-.113q.052-.053.113-.094t.13-.069t.141-.043t.146-.014zm3.5 0h3.25q.75 0 .75-.75t-.75-.75h-3.25z");
}

</style>
