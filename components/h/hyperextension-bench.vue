<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="je2f5d68g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:hyperextension-bench" /></template>
<style>
.je2f5d68g {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M16.75 6.5q0-2.5 2.5-2.5t2.5 2.5t-2.5 2.5t-2.5-2.5M4.263 10.788q-.916.306-1.348 1.169q-.432.864-.127 1.78q.306.916 1.169 1.348q.864.432 1.78.127l3.513-1.171v5.709H4q-.074 0-.146.014q-.073.015-.141.043t-.13.069t-.113.094q-.053.052-.094.113t-.069.13t-.043.141t-.014.146q0 .074.014.146q.015.073.043.141t.069.13q.041.061.094.113q.052.053.113.094t.13.069t.141.043t.146.014h13q.074 0 .146-.014q.073-.015.141-.043t.13-.069q.061-.041.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146q0-.074-.014-.146q-.015-.073-.043-.141t-.069-.13q-.041-.061-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043T17 19.75h-6.25v-6.209l3.987-1.329q.916-.306 1.348-1.169q.432-.864.127-1.78q-.306-.916-1.169-1.348q-.864-.432-1.78-.127z");
}

</style>
