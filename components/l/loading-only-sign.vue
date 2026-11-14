<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ef0pl8omh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:loading-only-sign" /></template>
<style>
.ef0pl8omh {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M4.399 4.399Q1.25 7.547 1.25 12t3.149 7.601Q7.547 22.75 12 22.75t7.601-3.149Q22.75 16.453 22.75 12t-3.149-7.601Q16.453 1.25 12 1.25T4.399 4.399m8.132 6.131h-.001q-.105.106-.243.163T12 10.75h-.004q-.148-.001-.285-.058t-.241-.162h-.001L8.72 7.78q-.053-.052-.094-.113t-.069-.13t-.043-.141T8.5 7.25t.014-.146q.015-.073.043-.141t.069-.13q.041-.061.094-.113q.105-.106.243-.163T9.25 6.5t.287.057t.243.163l1.47 1.469V5q0-.074.014-.146q.015-.073.043-.141t.069-.13q.041-.061.094-.113q.052-.053.113-.094t.13-.069t.141-.043T12 4.25t.146.014q.073.015.141.043t.13.069t.113.094q.053.052.094.113t.069.13t.043.141t.014.146v3.189l1.47-1.469q.105-.106.243-.163t.287-.057t.287.057t.243.163q.053.052.094.113t.069.13t.043.141t.014.146t-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113z");
}

</style>
