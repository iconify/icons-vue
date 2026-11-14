<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="co5dad7iq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:flatbed-truck" /></template>
<style>
.co5dad7iq {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M2.5 10.75h11.25V6.5q0-.074.014-.146q.015-.073.043-.141t.069-.13q.041-.061.094-.113q.052-.053.113-.094t.13-.069t.141-.043t.146-.014h4q.164 0 .313.069q.15.068.256.193l3 3.5q.088.102.134.228t.047.26v4.5q0 .074-.014.146q-.015.073-.043.141t-.069.13t-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014h-1.438q.188.531.188 1.25q0 2.75-2.75 2.75t-2.75-2.75q0-.719.188-1.25H9.562q.188.531.188 1.25q0 2.75-2.75 2.75T4.25 16.5q0-.719.188-1.25H2.5q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141q-.014-.072-.014-.146v-3q0-.074.014-.146q.015-.073.043-.141t.069-.13t.094-.113q.052-.053.113-.094t.13-.069t.141-.043t.146-.014");
}

</style>
