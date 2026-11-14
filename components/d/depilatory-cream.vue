<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k6rx3st8o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:depilatory-cream" /></template>
<style>
.k6rx3st8o {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M8.54 2.75h6.92q1.149 0 1.898.872t.573 2.008l-1.462 9.5q-.242 1.574-1.486 1.979q.267.515.267 1.141v.5q0 1.036-.732 1.768t-1.768.732h-1.5q-2.5 0-2.5-2.5v-.5q0-.677.183-1.17q-1.169-.43-1.402-1.95l-1.462-9.5q-.175-1.136.573-2.008q.749-.872 1.898-.872M11 8.125q-1.75 0-1.75 1.875q0 .074.014.146q.015.073.043.141t.069.13t.094.113q.052.053.113.094t.13.069t.141.043t.146.014t.146-.014q.073-.015.141-.043t.13-.069t.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146q0-.375.25-.375t.25.375q0 1.875 1.75 1.875T14.75 10q0-.074-.014-.146q-.015-.073-.043-.141t-.069-.13t-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043T14 9.25t-.146.014q-.073.015-.141.043t-.13.069t-.113.094q-.053.052-.094.113t-.069.13t-.043.141t-.014.146q0 .375-.25.375T12.75 10q0-1.875-1.75-1.875");
}

</style>
