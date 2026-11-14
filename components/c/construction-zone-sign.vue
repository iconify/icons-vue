<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f7qyxacqn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:construction-zone-sign" /></template>
<style>
.f7qyxacqn {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("m19.53 8.97l-7-7q-.105-.106-.243-.163T12 1.75t-.287.057t-.243.163l-7 7q-.106.105-.163.243T4.25 9.5t.057.287t.163.243l6.78 6.781v3.939H9q-.074 0-.146.014q-.073.015-.141.043t-.13.069t-.113.094q-.053.052-.094.113t-.069.13t-.043.141t-.014.146t.014.146q.015.073.043.141t.069.13q.041.061.094.113q.052.053.113.094t.13.069t.141.043t.146.014h6q.074 0 .146-.014q.073-.015.141-.043t.13-.069t.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146t-.014-.146q-.015-.073-.043-.141t-.069-.13q-.041-.061-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043T15 20.75h-2.25v-3.939l6.78-6.781q.053-.052.094-.113t.069-.13t.043-.141t.014-.146t-.014-.146q-.015-.073-.043-.141t-.069-.13t-.094-.113M12 15.439L6.061 9.5L12 3.561L17.939 9.5z");
}

</style>
