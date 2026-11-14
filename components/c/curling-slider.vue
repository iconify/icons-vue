<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yooxjn1_c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:curling-slider" /></template>
<style>
.yooxjn1_c {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M2.5 7v7q0 .074.014.146q.015.073.043.141t.069.13t.094.113q.052.053.113.094t.13.069t.141.043t.146.014h17.5q.074 0 .146-.014q.073-.015.141-.043t.13-.069q.061-.041.113-.094q.053-.052.094-.113t.069-.13t.043-.141T21.5 14q0-3.336-3.568-4.228l-.025-.005l-6.647-1.425l-1.839-3.677q-.047-.094-.117-.171t-.16-.132t-.189-.083q-.101-.029-.205-.029h-3.5q-1.139 0-1.945.805Q2.5 5.861 2.5 7m2 8.75h15q2 0 2 2t-2 2h-15q-2 0-2-2t2-2");
}

</style>
