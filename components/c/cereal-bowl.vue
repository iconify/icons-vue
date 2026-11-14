<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n2etv825f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:cereal-bowl" /></template>
<style>
.n2etv825f {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M4.75 4.25h1Q8 4.25 8 6.5v1q0 .413-.076.75h1.402q-.076-.337-.076-.75v-1q0-2.25 2.25-2.25h1q.932 0 1.591.659T14.75 6.5v1q0 .4-.121.75h1.447Q16 7.913 16 7.5v-1q0-2.25 2.25-2.25h1q2.25 0 2.25 2.25v1q0 .413-.076.75h.076q.074 0 .146.014q.073.015.141.043t.13.069q.061.041.113.094q.053.052.094.113t.069.13t.043.141t.014.146q0 4.686-3.095 7.78q-2.969 2.97-7.155 2.97t-7.155-2.97Q1.75 13.686 1.75 9q0-.074.014-.146q.015-.073.043-.141t.069-.13t.094-.113q.052-.053.113-.094t.13-.069t.141-.043t.146-.014h.076Q2.5 7.913 2.5 7.5v-1q0-.932.659-1.591T4.75 4.25");
}

</style>
