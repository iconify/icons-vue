<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dy6qwpnto"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:dj-cue" /></template>
<style>
.dy6qwpnto {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M18 3.25H6q-1.76 0-3.005 1.245T1.75 7.5v9q0 1.76 1.245 3.005T6 20.75h12q1.76 0 3.005-1.245T22.25 16.5v-9q0-1.76-1.245-3.005T18 3.25m1.25 13.25q0 .074-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069q-.061-.041-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141t-.014-.146v-9q0-.074.014-.146q.015-.073.043-.141t.069-.13q.041-.061.094-.113q.052-.053.113-.094t.13-.069t.141-.043t.146-.014q.074 0 .146.014q.073.015.141.043t.13.069q.061.041.113.094q.053.052.094.113t.069.13t.043.141t.014.146zm-7.188-6.853q-.469.853-1.442.853h-.24q-.973 0-1.442-.853t.054-1.674q.527-.828 1.508-.828t1.508.827v.001q.522.821.054 1.674");
}

</style>
