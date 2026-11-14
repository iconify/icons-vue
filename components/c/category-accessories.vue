<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ltelbacgy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:category-accessories" /></template>
<style>
.ltelbacgy {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M10 4.75H6.5q-1.76 0-3.005 1.245T2.25 9v6q0 1.76 1.245 3.005T6.5 19.25H10q1.76 0 3.005-1.245q1.156-1.155 1.239-2.755H19q.149 0 .287-.057t.243-.163l2.5-2.5q.053-.052.094-.113t.069-.13t.043-.141t.014-.146t-.014-.146q-.015-.073-.043-.141t-.069-.13t-.094-.113l-2.5-2.5q-.105-.106-.243-.163T19 8.75h-4.756q-.083-1.6-1.239-2.755Q11.76 4.75 10 4.75m8.689 9H14.25v-3.5h4.439l1.75 1.75zm-1.679-2.5H17q-.074 0-.146.014q-.073.015-.141.043t-.13.069q-.061.041-.113.094q-.053.052-.094.113t-.069.13t-.043.141t-.014.146t.014.146q.015.073.043.141t.069.13t.094.113q.052.053.113.094t.13.069t.141.043t.146.014h.01q.074 0 .146-.014q.073-.015.141-.043t.13-.069t.113-.094q.053-.052.094-.113t.069-.13t.043-.141q.014-.072.014-.146t-.014-.146q-.015-.073-.043-.141t-.069-.13t-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043t-.146-.014");
}

</style>
