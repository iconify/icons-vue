<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rzmfxigbf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:careers-page" /></template>
<style>
.rzmfxigbf {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M18 2.75H6q-1.76 0-3.005 1.245T1.75 7v10q0 1.76 1.245 3.005T6 21.25h12q1.76 0 3.005-1.245T22.25 17V7q0-1.76-1.245-3.005T18 2.75m4.25 4.75q0 .074-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014h-19q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141T1.75 7.5t.014-.146q.015-.073.043-.141t.069-.13q.041-.061.094-.113q.052-.053.113-.094t.13-.069t.141-.043t.146-.014h19q.074 0 .146.014q.073.015.141.043t.13.069q.061.041.113.094q.053.052.094.113t.069.13t.043.141t.014.146M11 11.5v-.25q0-.25.25-.25h1.5q.25 0 .25.25v.25zm3.5.003q2.75.093 2.75 2.935v1.125q-.001 2.936-2.937 2.937H9.688q-2.937 0-2.938-2.937v-1.125q0-1.217.861-2.077q.793-.794 1.889-.856v-.255q0-1.75 1.75-1.75h1.5q1.75 0 1.75 1.75z");
}

</style>
