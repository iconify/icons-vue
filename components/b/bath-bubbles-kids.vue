<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ma7tgbbps"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:bath-bubbles-kids" /></template>
<style>
.ma7tgbbps {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M12.25 2.25Q9.5 2.25 9.5 5t2.75 2.75T15 5t-2.75-2.75M3.75 8.5q0-2.75 2.75-2.75T9.25 8.5T6.5 11.25T3.75 8.5m11.5.5q0-2.25 2.25-2.25T19.75 9t-2.25 2.25T15.25 9M2.5 12.75h19q.074 0 .146.014q.073.015.141.043t.13.069q.061.041.113.094q.053.052.094.113t.069.13t.043.141t.014.146t-.014.146q-.015.073-.043.141t-.069.13t-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014h-1.25v2.25q0 1.968-1.391 3.359T15.5 21.25h-7q-1.968 0-3.359-1.391T3.75 16.5v-2.25H2.5q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141q-.014-.072-.014-.146t.014-.146q.015-.073.043-.141t.069-.13t.094-.113q.052-.053.113-.094t.13-.069t.141-.043t.146-.014m16.25 1.5H5.25v2.25q0 3.25 3.25 3.25h7q3.25 0 3.25-3.25z");
}

</style>
