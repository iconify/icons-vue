<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rv08lgbub"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:ladderway" /></template>
<style>
.rv08lgbub {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M8.5 1.75h7q.074 0 .146.014q.073.015.141.043t.13.069t.113.094q.053.052.094.113t.069.13t.043.141t.014.146v13.193q6 .629 6 3.307q0 3.5-10.25 3.5q-4.041 0-6.926-.835Q1.75 20.703 1.75 19q0-2.678 6-3.307V2.5q0-.074.014-.146q.015-.073.043-.141t.069-.13t.094-.113q.052-.053.113-.094t.13-.069t.141-.043q.072-.014.146-.014m.75 12.5v1.323Q10.518 15.5 12 15.5t2.75.073V14.25zm5.5-1.5V11.5h-5.5v1.25zm0-9.5h-5.5V4.5h5.5zm0 4V6h-5.5v1.25zm0 1.5h-5.5V10h5.5z");
}

</style>
