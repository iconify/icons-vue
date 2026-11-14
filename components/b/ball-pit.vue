<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tbapytpfc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:ball-pit" /></template>
<style>
.tbapytpfc {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M8.75 6.25Q8.75 3 12 3t3.25 3.25q0 .568-.099 1.036q2.599.308 2.599 3.214q0 1.042-.334 1.75H21.5q.074 0 .146.014q.073.015.141.043t.13.069q.061.041.113.094q.053.052.094.113t.069.13t.043.141t.014.146t-.014.146q-.015.073-.043.141t-.069.13t-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014h-.75v3.75q0 3.25-3.25 3.25h-11q-3.25 0-3.25-3.25v-3.75H2.5q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141Q1.75 13.074 1.75 13t.014-.146q.015-.073.043-.141t.069-.13t.094-.113q.052-.053.113-.094t.13-.069t.141-.043t.146-.014h4.084q-.334-.708-.334-1.75q0-2.906 2.599-3.214q-.099-.468-.099-1.036m-4 7.5h14.5v3.75q0 1.75-1.75 1.75h-11q-1.75 0-1.75-1.75z");
}

</style>
