<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ncwf07shf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:crater-lake" /></template>
<style>
.ncwf07shf {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("m7.85 6.697l-4.875 10.5q-.577 1.243.16 2.398t2.107 1.155h13.516q1.37 0 2.107-1.155t.16-2.398l-4.875-10.5q-.672-1.447-2.267-1.447h-3.766q-1.595 0-2.267 1.447m4.68 4.273q.72.719 1.44 0q.052-.053.113-.094t.13-.069t.141-.043t.146-.014t.146.014q.073.015.141.043t.13.069t.113.094q.053.052.094.113t.069.13t.043.141t.014.146t-.014.146q-.015.073-.043.141t-.069.13t-.094.113q-1.78 1.781-3.56 0q-.72-.719-1.44 0q-.052.053-.113.094t-.13.069t-.141.043t-.146.014t-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141t-.014-.146t.014-.146q.015-.073.043-.141t.069-.13t.094-.113q1.78-1.781 3.56 0");
}

</style>
