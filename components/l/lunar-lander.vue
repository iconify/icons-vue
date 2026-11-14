<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yttb37bcj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:lunar-lander" /></template>
<style>
.yttb37bcj {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M14.297 2.75H9.703q-1.054 0-1.729.81L6.272 5.603q-.522.625-.522 1.44V10q0 1.318.772 1.864L3.509 18.75H2.5q-.074 0-.146.014q-.073.015-.141.043t-.13.069t-.113.094q-.053.052-.094.113t-.069.13t-.043.141t-.014.146t.014.146q.015.073.043.141t.069.13q.041.061.094.113q.052.053.113.094t.13.069t.141.043t.146.014h19q.074 0 .146-.014q.073-.015.141-.043t.13-.069q.061-.041.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146q0-.074-.014-.146q-.015-.073-.043-.141t-.069-.13q-.041-.061-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043t-.146-.014h-1.009l-3.013-6.886q.772-.546.772-1.864V7.043q0-.815-.522-1.44L16.026 3.56q-.675-.81-1.729-.81m4.556 16h-3.441l-.812-6.5h1.409zm-4.953 0l-.812-6.5h-2.176l-.812 6.5zm-5.312 0l.812-6.5H7.991l-2.844 6.5z");
}

</style>
