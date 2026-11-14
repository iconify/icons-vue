<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tex5awb_e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:defect-tag" /></template>
<style>
.tex5awb_e {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M14.75 7.25H15q.149 0 .287.057t.243.163l4 4q.106.105.163.243t.057.287v7.5q0 2.75-2.75 2.75H7q-2.75 0-2.75-2.75V12q0-.149.057-.287t.163-.243l4-4q.105-.106.243-.163T9 7.25h.25V5.5q0-2.75 2.75-2.75t2.75 2.75zm-4 0V5.5q0-1.25 1.25-1.25t1.25 1.25v1.75zm3.72 4.72l-6 6q-.053.052-.094.113t-.069.13t-.043.141t-.014.146t.014.146q.015.073.043.141t.069.13q.041.061.094.113q.105.106.243.163T9 19.25t.287-.057t.243-.163l6-6q.053-.052.094-.113t.069-.13t.043-.141t.014-.146t-.014-.146q-.015-.073-.043-.141t-.069-.13t-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043T15 11.75t-.146.014q-.073.015-.141.043t-.13.069t-.113.094");
}

</style>
