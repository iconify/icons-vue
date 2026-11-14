<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rbzttubzn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:category-baby-feeding" /></template>
<style>
.rbzttubzn {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M9.25 7q0-4.25 2.75-4.25T14.75 7v2.441q3 1.042 3 4.559v5q0 2.75-2.75 2.75H9q-2.75 0-2.75-2.75v-5q0-3.517 3-4.559zM12 4.25q-1.066 0-1.223 2h2.446q-.157-2-1.223-2m-1 10H8.5q-.074 0-.146.014q-.073.015-.141.043t-.13.069t-.113.094q-.053.052-.094.113t-.069.13t-.043.141T7.75 15t.014.146q.015.073.043.141t.069.13t.094.113q.052.053.113.094t.13.069t.141.043t.146.014H11q.074 0 .146-.014q.073-.015.141-.043t.13-.069t.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146t-.014-.146q-.015-.073-.043-.141t-.069-.13t-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043T11 14.25");
}

</style>
