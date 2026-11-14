<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="modg9o_hc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:kidney-single" /></template>
<style>
.modg9o_hc {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M17.018 3.989Q15.72 2.75 13.5 2.75q-3.666 0-6.007 2.731Q5.25 8.098 5.25 12t2.243 6.519Q9.834 21.25 13.5 21.25q2.22 0 3.518-1.239q1.423-1.358.964-3.424q-.217-.948-1.349-2.343q-.689-.848-.959-1.494H20q.074 0 .146-.014q.073-.015.141-.043t.13-.069q.061-.041.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146t-.014-.146q-.015-.073-.043-.141t-.069-.13t-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043T20 11.25h-4.326q.27-.646.959-1.494q1.132-1.395 1.348-2.339q.46-2.07-.963-3.428");
}

</style>
