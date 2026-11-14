<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nt0us5ooq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:alternate-glyph" /></template>
<style>
.nt0us5ooq {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M4.873 6.373Q2.75 8.497 2.75 11.5t2.123 5.127T10 18.75t5.127-2.123q.338-.339.623-.7v.573q0 4.25 3.5 4.25q3 0 3-3.25q0-.074-.014-.146q-.015-.073-.043-.141t-.069-.13q-.041-.061-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043t-.146-.014q-.074 0-.146.014q-.073.015-.141.043t-.13.069q-.061.041-.113.094q-.053.052-.094.113t-.069.13t-.043.141t-.014.146q0 1.75-1.5 1.75q-2 0-2-2.75V5q0-.074-.014-.146q-.015-.073-.043-.141t-.069-.13q-.041-.061-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043t-.146-.014q-.074 0-.146.014q-.073.015-.141.043t-.13.069q-.061.041-.113.094q-.053.052-.094.113t-.069.13t-.043.141T15.75 5v2.073q-.285-.361-.623-.7Q13.003 4.25 10 4.25T4.873 6.373");
}

</style>
