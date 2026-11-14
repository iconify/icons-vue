<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v8vt7szae"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:formwork" /></template>
<style>
.v8vt7szae {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M9.25 5.5q0-2.25-2.25-2.25T4.75 5.5v1.75H3q-.074 0-.146.014q-.073.015-.141.043t-.13.069t-.113.094q-.053.052-.094.113t-.069.13t-.043.141Q2.25 7.926 2.25 8t.014.146t.043.141t.069.13t.094.113q.052.053.113.094t.13.069t.141.043T3 8.75h1.75V16q0 .413.076.75H4.25q-1.036 0-1.768.732T1.75 19.25t.732 1.768t1.768.732h15.5q1.036 0 1.768-.732t.732-1.768t-.732-1.768t-1.768-.732h-.576q.076-.337.076-.75V8.75H21q.074 0 .146-.014q.073-.015.141-.043t.13-.069q.061-.041.113-.094q.053-.052.094-.113t.069-.13t.043-.141T21.75 8t-.014-.146q-.015-.073-.043-.141t-.069-.13q-.041-.061-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043T21 7.25h-1.75V5.5q0-2.25-2.25-2.25T14.75 5.5v1.75h-5.5zm0 3.25V16q0 .413-.076.75h5.652q-.076-.337-.076-.75V8.75z");
}

</style>
