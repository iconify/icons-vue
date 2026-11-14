<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f7jqjbs4k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:dried-mango" /></template>
<style>
.f7jqjbs4k {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M5.5 6.5h-3q-.149 0-.287.057t-.243.163t-.163.243t-.057.287q0 4.246 3.002 7.248T12 17.5t7.248-3.002T22.25 7.25q0-.074-.014-.146q-.015-.073-.043-.141t-.069-.13q-.041-.061-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043T21.5 6.5zm0 0q.074 0 .146.014q.073.015.141.043t.13.069q.061.041.113.094q.053.052.094.113t.069.13t.043.141t.014.146q0 2.382 1.684 4.066T12 13t4.066-1.684T17.75 7.25q0-.074.014-.146q.015-.073.043-.141t.069-.13q.041-.061.094-.113q.052-.053.113-.094t.13-.069t.141-.043t.146-.014q.074 0 .146.014q.073.015.141.043t.13.069q.061.041.113.094q.053.052.094.113t.069.13t.043.141t.014.146q0 3.003-2.123 5.127T12 14.5t-5.127-2.123T4.75 7.25q0-.074.014-.146q.015-.073.043-.141t.069-.13q.041-.061.094-.113q.052-.053.113-.094t.13-.069t.141-.043T5.5 6.5");
}

</style>
