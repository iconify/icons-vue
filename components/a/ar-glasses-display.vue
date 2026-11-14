<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qnh1pebha"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:ar-glasses-display" /></template>
<style>
.qnh1pebha {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M9.859 8.141Q8.468 6.75 6.5 6.75T3.141 8.141T1.75 11.5v1q0 1.968 1.391 3.359T6.5 17.25t3.359-1.391T11.25 12.5v-1q0-.325-.038-.634q.788-.641 1.576 0q-.038.309-.038.634v1q0 1.968 1.391 3.359T17.5 17.25t3.359-1.391T22.25 12.5v-1q0-1.968-1.391-3.359T17.5 6.75t-3.359 1.391q-.554.555-.888 1.2q-1.253-.773-2.506 0q-.334-.645-.888-1.2M18.75 11q.074 0 .146.014q.073.015.141.043t.13.069q.061.041.113.094q.053.052.094.113t.069.13t.043.141t.014.146t-.014.146q-.015.073-.043.141t-.069.13t-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014H16.5q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069q-.061-.041-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141t-.014-.146t.014-.146q.015-.073.043-.141t.069-.13t.094-.113q.052-.053.113-.094t.13-.069t.141-.043T16.5 11z");
}

</style>
