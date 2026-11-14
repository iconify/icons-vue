<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fp460ebtp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:carriage-number" /></template>
<style>
.fp460ebtp {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M1.75 16.5V8q0-5.25 10.25-5.25T22.25 8v8.5q0 .074-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014h-1.438q.188.531.188 1.25q0 2.75-2.75 2.75t-2.75-2.75q0-.719.188-1.25H9.062q.188.531.188 1.25q0 2.75-2.75 2.75T3.75 18.5q0-.719.188-1.25H2.5q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141t-.014-.146m7-9.75q-2.5 0-2.5 2.5v2q0 2.5 2.5 2.5h6.5q2.5 0 2.5-2.5v-2q0-2.5-2.5-2.5z");
}

</style>
