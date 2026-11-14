<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kebaknrdn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:barbless-hook" /></template>
<style>
.kebaknrdn {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M16 1.75q-2.25 0-2.25 2.25q0 1.837 1.5 2.174V15q0 3.75-3.75 3.75T7.75 15v-3.5q0-.074-.014-.146q-.015-.073-.043-.141t-.069-.13t-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043T7 10.75t-.146.014q-.073.015-.141.043t-.13.069q-.061.041-.113.094q-.053.052-.094.113t-.069.13t-.043.141t-.014.146V15q0 2.175 1.538 3.712Q9.325 20.25 11.5 20.25t3.712-1.538Q16.75 17.175 16.75 15V6.174q1.5-.337 1.5-2.174q0-2.25-2.25-2.25");
}

</style>
