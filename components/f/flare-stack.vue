<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dvmvw7akg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:flare-stack" /></template>
<style>
.dvmvw7akg {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M12.436 1.89q2.886 2.061 2.75 4.097Q15.035 8.25 12 8.25T8.814 5.987q-.136-2.036 2.75-4.097q.047-.034.1-.06q.052-.026.107-.044q.056-.018.113-.027q.058-.009.116-.009t.116.009t.113.027t.107.044t.1.06M9.25 12q0-2.25 2.25-2.25h1q.932 0 1.591.659T14.75 12v8q0 .4-.121.75H18q.074 0 .146.014q.073.015.141.043t.13.069q.061.041.113.094q.053.052.094.113t.069.13t.043.141t.014.146q0 .074-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014H6q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069q-.061-.041-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141t-.014-.146q0-.074.014-.146q.015-.073.043-.141t.069-.13q.041-.061.094-.113q.052-.053.113-.094t.13-.069t.141-.043T6 20.75h3.326q-.076-.337-.076-.75z");
}

</style>
