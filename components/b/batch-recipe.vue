<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ojzngnbco"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:batch-recipe" /></template>
<style>
.ojzngnbco {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M9.331 6.25Q9.96 3.5 15.5 3.5q6.25 0 6.25 3.5t-6.25 3.5q-5.54 0-6.169-2.75H3q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141Q2.25 7.074 2.25 7t.014-.146t.043-.141t.069-.13t.094-.113q.052-.053.113-.094t.13-.069t.141-.043T3 6.25zM3 11.75h18q.074 0 .146.014q.073.015.141.043t.13.069q.061.041.113.094q.053.052.094.113t.069.13t.043.141t.014.146q0 4.03-2.866 6.676Q16.095 21.75 12 21.75t-6.884-2.574Q2.25 16.53 2.25 12.5q0-.074.014-.146q.015-.073.043-.141t.069-.13t.094-.113q.052-.053.113-.094t.13-.069t.141-.043T3 11.75");
}

</style>
