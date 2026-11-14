<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="il59nkbvg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:cement-works" /></template>
<style>
.il59nkbvg {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M21.5 21.75h-19q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141T1.75 21t.014-.146q.015-.073.043-.141t.069-.13q.041-.061.094-.113q.052-.053.113-.094t.13-.069t.141-.043t.146-.014h1.25V7q0-1.76 1.245-3.005T8 2.75t3.005 1.245T12.25 7v.631l6.005 4.619H20.5q.074 0 .146.014q.073.015.141.043t.13.069q.061.041.113.094q.053.052.094.113t.069.13t.043.141t.014.146v7.25h.25q.074 0 .146.014q.073.015.141.043t.13.069q.061.041.113.094q.053.052.094.113t.069.13t.043.141t.014.146q0 .074-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014m-5.705-9.5L12.25 9.523v2.727zM5.25 9.75V7q0-2.75 2.75-2.75T10.75 7v2.75zm0 1.5v4h5.5v-4zm7 9h7.5v-6.5h-7.5zm-7 0h5.5v-3.5h-5.5z");
}

</style>
