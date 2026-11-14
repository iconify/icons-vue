<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zbnjzsbgv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:dairy-free-mark" /></template>
<style>
.zbnjzsbgv {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9.474 5.537L9.5 5.5v-3h5v3L17 9v4.099m-.187 7.626q-.048.088-.108.168t-.129.152q-.07.072-.149.134t-.165.113t-.178.09t-.189.065t-.196.04t-.199.013h-7q-.074 0-.147-.007t-.146-.022t-.142-.036q-.071-.021-.139-.049t-.133-.063t-.126-.076t-.119-.087q-.057-.047-.109-.099t-.099-.109q-.046-.057-.087-.119t-.076-.126q-.035-.065-.063-.133t-.049-.139q-.022-.07-.036-.142q-.015-.073-.022-.146T7 20v-9.056M3.5 3.5l17 17");
}

</style>
