<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ab6zo4b5v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:ink-drops-cmyk" /></template>
<style>
.ab6zo4b5v {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M8.03 2.47q-.052-.053-.113-.094t-.13-.069t-.141-.043T7.5 2.25t-.146.014q-.073.015-.141.043t-.13.069q-.061.041-.113.094Q3.75 5.689 3.75 7.5q0 3.75 3.75 3.75t3.75-3.75q0-1.811-3.22-5.03m7.94 0q.052-.053.113-.094t.13-.069t.141-.043t.146-.014q.074 0 .146.014q.073.015.141.043t.13.069q.061.041.113.094q3.22 3.219 3.22 5.03q0 3.75-3.75 3.75T12.75 7.5q0-1.811 3.22-5.03M7.5 12.75q-.149 0-.287.057t-.243.163Q3.75 16.189 3.75 18q0 3.75 3.75 3.75T11.25 18q0-1.811-3.22-5.03q-.105-.106-.243-.163T7.5 12.75m8.47.22q.105-.106.243-.163t.287-.057t.287.057t.243.163q3.22 3.219 3.22 5.03q0 3.75-3.75 3.75T12.75 18q0-1.811 3.22-5.03");
}

</style>
