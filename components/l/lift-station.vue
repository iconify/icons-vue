<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lv-geabiw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:lift-station" /></template>
<style>
.lv-geabiw {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M2.5 2.25h19q.074 0 .146.014q.073.015.141.043t.13.069q.061.041.113.094q.053.052.094.113t.069.13t.043.141t.014.146t-.014.146q-.015.073-.043.141t-.069.13t-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014h-6.938q.188.531.188 1.25q0 2.345-2 2.69v.973q.287.102.574.281l6.25 3.906q1.176.734 1.176 2.12v4.28q0 1.036-.732 1.768t-1.768.732H12.5q.932 0 1.591-.659t.659-1.591v-2q0-.932-.659-1.591T12.5 15.25h-1q-2.25 0-2.25 2.25v2q0 2.25 2.25 2.25H5.75q-1.036 0-1.768-.732T3.25 19.25v-4.28q0-1.386 1.176-2.12l6.25-3.906q.287-.179.574-.281V7.69q-2-.345-2-2.69q0-.719.188-1.25H2.5q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141Q1.75 3.074 1.75 3t.014-.146t.043-.141t.069-.13t.094-.113q.052-.053.113-.094t.13-.069t.141-.043q.072-.014.146-.014");
}

</style>
