<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k4f8l4bff"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:logic-gate-not" /></template>
<style>
.k4f8l4bff {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("m7.645 6.191l6.552 3.872q.912.54 1.071 1.51Q15.472 9.25 18 9.25q2.75 0 2.75 2.75T18 14.75q-2.528 0-2.732-2.323q-.158.97-1.071 1.51l-6.552 3.872q-1.126.664-2.261.017q-1.134-.648-1.134-1.955V12.75H2.5q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141Q1.75 12.074 1.75 12t.014-.146q.015-.073.043-.141t.069-.13t.094-.113q.052-.053.113-.094t.13-.069t.141-.043t.146-.014h1.75V8.129q0-1.307 1.134-1.955q1.135-.647 2.26.017z");
}

</style>
