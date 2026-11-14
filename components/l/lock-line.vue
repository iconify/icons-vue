<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fplie458h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:lock-line" /></template>
<style>
.fplie458h {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M16.75 9.499q1.109.362 1.999 1.252q1.501 1.501 1.501 3.624v2.75q0 2.123-1.501 3.624t-3.624 1.501h-6.25q-2.123 0-3.624-1.501T3.75 17.125v-2.75q0-2.123 1.501-3.624q.89-.89 1.999-1.252V7q0-1.968 1.391-3.359T12 2.25t3.359 1.391T16.75 7zm-8-.248l.125-.001h6.25l.125.001V7q0-3.25-3.25-3.25T8.75 7zm4 8.249V14q0-.074-.014-.146q-.015-.073-.043-.141t-.069-.13t-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043T12 13.25t-.146.014q-.073.015-.141.043t-.13.069t-.113.094q-.053.052-.094.113t-.069.13t-.043.141t-.014.146v3.5q0 .074.014.146q.015.073.043.141t.069.13q.041.061.094.113q.052.053.113.094t.13.069t.141.043t.146.014t.146-.014q.073-.015.141-.043t.13-.069t.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146");
}

</style>
