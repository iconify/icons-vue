<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fw_jgnbot"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:fault-line" /></template>
<style>
.fw_jgnbot {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M15 4h4.5q2.75 0 2.75 2.75v8q0 2.75-2.75 2.75h-5q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141t-.014-.146q0-.159.065-.305l1.79-4.029L12.97 9.78q-.074-.074-.125-.165t-.075-.193t-.019-.206t.037-.203l1.5-4.5q.019-.056.046-.108t.062-.099t.076-.089t.089-.075q.048-.035.1-.061q.053-.027.109-.045q.055-.018.113-.027T15 4m-4 2.5H4.5q-1.139 0-1.945.805q-.805.806-.805 1.945v8Q1.75 20 4.5 20h6q.109 0 .213-.031t.196-.09q.091-.059.162-.142q.07-.083.114-.182l2-4.5q.047-.104.06-.217t-.008-.225t-.073-.212t-.134-.181l-2.672-2.673l1.354-4.06q.038-.115.038-.237q0-.074-.014-.146q-.015-.073-.043-.141t-.069-.13q-.041-.061-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043T11 6.5");
}

</style>
