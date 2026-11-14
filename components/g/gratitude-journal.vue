<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q1igm4boo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:gratitude-journal" /></template>
<style>
.q1igm4boo {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M8.5 1.75h7q1.76 0 3.005 1.245T19.75 6v12q0 1.76-1.245 3.005T15.5 22.25h-7q.074 0 .146-.014q.073-.015.141-.043t.13-.069t.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146v-19q0-.074-.014-.146q-.015-.073-.043-.141t-.069-.13t-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043Q8.574 1.75 8.5 1.75m0 0q-.074 0-.146.014q-.073.015-.141.043t-.13.069t-.113.094q-.053.052-.094.113t-.069.13t-.043.141t-.014.146v19q0 .074.014.146q.015.073.043.141t.069.13q.041.061.094.113q.052.053.113.094t.13.069t.141.043t.146.014q-1.76 0-3.005-1.245T4.25 18V6q0-1.76 1.245-3.005T8.5 1.75m4.857 13.889q.089.054.189.083q.1.028.204.028t.204-.028t.189-.083q3.607-2.22 3.607-4.889q0-2.5-2.5-2.5q-.89 0-1.5.523q-.61-.523-1.5-.523q-2.5 0-2.5 2.5q0 2.669 3.607 4.889");
}

</style>
