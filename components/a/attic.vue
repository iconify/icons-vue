<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fcjoimn9n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:attic" /></template>
<style>
.fcjoimn9n {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("m3.023 9.921l8.5-7q.05-.041.106-.073q.057-.032.118-.054t.124-.033T12 2.75t.129.011t.124.033t.118.054q.056.032.106.073l8.5 7q.115.095.185.227q.07.131.085.28q.003.036.003.072V21q0 .074-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014h-17q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141T2.75 21V10.5q0-.168.072-.32q.071-.152.201-.259M10.75 20.25h2.5v-2.5h-2.5zm4 0h5v-9H4.25v9h5V17q0-.074.014-.146q.015-.073.043-.141t.069-.13q.041-.061.094-.113q.052-.053.113-.094t.13-.069t.141-.043t.146-.014h4q.074 0 .146.014q.073.015.141.043t.13.069t.113.094q.053.052.094.113t.069.13t.043.141t.014.146z");
}

</style>
