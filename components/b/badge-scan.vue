<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c2-cqkbam"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:badge-scan" /></template>
<style>
.c2-cqkbam {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M14.75 5.25V2.5q0-.074-.014-.146q-.015-.073-.043-.141t-.069-.13t-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043Q14.074 1.75 14 1.75t-.146.014q-.073.015-.141.043t-.13.069t-.113.094q-.053.052-.094.113t-.069.13t-.043.141t-.014.146v2.75h-2.5V2.5q0-.074-.014-.146q-.015-.073-.043-.141t-.069-.13t-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043Q10.074 1.75 10 1.75t-.146.014q-.073.015-.141.043t-.13.069t-.113.094q-.053.052-.094.113t-.069.13t-.043.141t-.014.146v2.75H8q-1.76 0-3.005 1.245T3.75 9.5V18h4.036q.357-3.5 4.214-3.5t4.214 3.5h4.036V9.5q0-1.76-1.245-3.005T16 5.25zm5.241 14.25H4.009q.309.829.986 1.505Q6.24 22.25 8 22.25h8q1.76 0 3.005-1.245q.677-.676.986-1.505M9.31 18h5.38q-.345-2-2.69-2t-2.69 2m.19-7.5Q9.5 8 12 8q1.036 0 1.768.732T14.5 10.5t-.732 1.768T12 13q-2.5 0-2.5-2.5");
}

</style>
