<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c9ajndxqc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:hero-astronaut" /></template>
<style>
.c9ajndxqc {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M3.75 17.5v-7q0-3.417 2.416-5.834T12 2.25t5.834 2.416Q20.25 7.083 20.25 10.5v7q0 .074-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014h-1.45q.2.459.2 1v.5q0 1.036-.732 1.768t-1.768.732h-7.5q-1.036 0-1.768-.732T5.75 19.75v-.5q0-.541.2-1H4.5q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069q-.061-.041-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141t-.014-.146m7-10.25q-4 0-4 4t4 4h2.5q1.657 0 2.828-1.172q1.172-1.171 1.172-2.828q0-4-4-4z");
}

</style>
