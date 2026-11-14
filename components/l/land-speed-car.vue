<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h39zv2clm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:land-speed-car" /></template>
<style>
.h39zv2clm {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M1.75 14V6.5q0-.074.014-.146q.015-.073.043-.141t.069-.13q.041-.061.094-.113q.052-.053.113-.094t.13-.069t.141-.043t.146-.014q.149 0 .287.057t.243.163l3.281 3.28h2.488Q9.15 6.75 12 6.75q2.988 0 3.229 2.746l6.566 2.815q.068.029.129.071t.113.094q.051.053.092.115q.04.062.067.13q.028.069.041.142t.013.146q-.001.074-.016.146q-.016.073-.045.14q-.057.133-.159.235l-1 1q-.105.106-.243.163t-.287.057h-1.438q.188.531.188 1.25q0 2.75-2.75 2.75T13.75 16q0-.719.188-1.25H9.062q.188.531.188 1.25q0 2.75-2.75 2.75T3.75 16q0-.719.188-1.25H2.5q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141Q1.75 14.074 1.75 14");
}

</style>
