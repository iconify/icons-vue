<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hm9m9jboi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:correction-fluid" /></template>
<style>
.hm9m9jboi {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M13.25 3.75h-2.5q-2.5 0-2.5 2.5v1q0 .651.17 1.133q-2.17.536-2.17 3.242v7.25q0 3.375 3.375 3.375h4.75q3.375 0 3.375-3.375v-7.25q0-2.758-2.253-3.262q.253-.504.253-1.113v-1q0-1.036-.732-1.768T13.25 3.75m1.25 9.5q.074 0 .146.014q.073.015.141.043t.13.069t.113.094q.053.052.094.113t.069.13t.043.141t.014.146t-.014.146q-.015.073-.043.141t-.069.13t-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014h-5q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141T8.75 14t.014-.146q.015-.073.043-.141t.069-.13t.094-.113q.052-.053.113-.094t.13-.069t.141-.043t.146-.014z");
}

</style>
