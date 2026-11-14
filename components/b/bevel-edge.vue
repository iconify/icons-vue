<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p5uyp1pet"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:bevel-edge" /></template>
<style>
.p5uyp1pet {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M2.25 9v12q0 .074.014.146q.015.073.043.141t.069.13q.041.061.094.113q.052.053.113.094t.13.069t.141.043t.146.014h12q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141T14.25 21v-7.689L10.689 9.75H3q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141Q2.25 9.074 2.25 9m.22-.531q.106-.105.243-.162q.138-.057.287-.057h7.689l5.781-5.78q.105-.106.243-.163T17 2.25H9q-.149 0-.287.057t-.243.163zM17.53 2.47q.106.105.163.243T17.75 3t-.057.287t-.163.243L12.061 9L15 11.939l5.47-5.469q.052-.053.113-.094t.13-.069t.141-.043T21 6.25q.074 0 .146.014q.073.015.141.043t.13.069q.061.041.113.094zM21.75 7q0 .149-.057.287t-.163.243l-5.78 5.781V21q0 .149-.057.287t-.163.243l6-6q.106-.105.163-.243T21.75 15z");
}

</style>
