<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gi4qy0abm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:cost-center-tag" /></template>
<style>
.gi4qy0abm {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M9.793 4.75h8.082q3.375 0 3.375 3.375v7.75q0 3.375-3.375 3.375H9.793q-1.662 0-2.676-1.318l-2.98-3.875Q2.555 12 4.136 9.943l2.982-3.875Q8.131 4.75 9.793 4.75m-1.293 5q-2.25 0-2.25 2.25t2.25 2.25T10.75 12T8.5 9.75m8.5 1.5h-4.25q-.074 0-.146.014q-.073.015-.141.043t-.13.069t-.113.094q-.053.052-.094.113t-.069.13t-.043.141T12 12t.014.146q.015.073.043.141t.069.13t.094.113q.052.053.113.094t.13.069t.141.043t.146.014H17q.074 0 .146-.014q.073-.015.141-.043t.13-.069q.061-.041.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146t-.014-.146q-.015-.073-.043-.141t-.069-.13t-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043T17 11.25");
}

</style>
