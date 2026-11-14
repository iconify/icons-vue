<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hvz88tb9h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:collection-tin" /></template>
<style>
.hvz88tb9h {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M9.25 4q0-1.375.688-2.062q.687-.688 2.062-.688q2.75 0 2.75 2.75T12 6.75T9.25 4M12 8q-6.75 0-6.75 3.5v8q0 3 6.75 3t6.75-3v-8Q18.75 8 12 8m1.5 2.75q.074 0 .146.014q.073.015.141.043t.13.069t.113.094q.053.052.094.113t.069.13t.043.141t.014.146t-.014.146q-.015.073-.043.141t-.069.13t-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014h-3q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141t-.014-.146t.014-.146q.015-.073.043-.141t.069-.13t.094-.113q.052-.053.113-.094t.13-.069t.141-.043t.146-.014zM6.75 19.5v-5.478Q8.432 15 12 15t5.25-.978V19.5q0 1.5-5.25 1.5t-5.25-1.5");
}

</style>
