<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="drmm_oh-j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:hydrogen-truck" /></template>
<style>
.drmm_oh-j {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M5.5 4.75h3q3.75 0 3.75 3.75T8.5 12.25h-3q-3.75 0-3.75-3.75T5.5 4.75m8.25 9H2.5q-.074 0-.146.014q-.073.015-.141.043t-.13.069t-.113.094q-.053.052-.094.113t-.069.13t-.043.141q-.014.072-.014.146t.014.146q.015.073.043.141t.069.13t.094.113q.052.053.113.094t.13.069t.141.043t.146.014h1.938q-.188.531-.188 1.25q0 2.75 2.75 2.75t2.75-2.75q0-.719-.188-1.25h5.376q-.188.531-.188 1.25q0 2.75 2.75 2.75t2.75-2.75q0-.719-.188-1.25H21.5q.074 0 .146-.014q.073-.015.141-.043t.13-.069q.061-.041.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146V10q0-.134-.047-.26q-.046-.126-.134-.228l-3-3.5q-.106-.125-.256-.193q-.149-.069-.313-.069h-4q-.074 0-.146.014q-.073.015-.141.043t-.13.069t-.113.094q-.053.052-.094.113t-.069.13t-.043.141t-.014.146zm7 0h-5.5v-6.5h2.905l2.595 3.027z");
}

</style>
