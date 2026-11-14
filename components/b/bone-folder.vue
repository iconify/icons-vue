<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dca0tibps"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:bone-folder" /></template>
<style>
.dca0tibps {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M4.97 22.03q.051.051.111.092q.06.04.126.068q.067.029.137.044t.143.016t.143-.011q.072-.013.139-.039t.129-.064t.114-.088q7.536-7.033 14.567-15.571q.058-.071.098-.154q.685-1.435-.44-2.56t-2.56-.44q-.083.04-.154.098q-8.538 7.031-15.571 14.567q-.05.053-.088.114t-.064.129q-.026.067-.039.139q-.012.071-.011.143t.016.143t.044.137q.028.066.068.126t.092.111zm3.5-7.56q.052-.053.113-.094t.13-.069t.141-.043T9 14.25t.146.014q.073.015.141.043t.13.069t.113.094q.053.052.094.113t.069.13t.043.141t.014.146t-.014.146q-.015.073-.043.141t-.069.13t-.094.113l-3.5 3.5q-.105.106-.243.163t-.287.057t-.287-.057t-.243-.163q-.053-.052-.094-.113t-.069-.13t-.043-.141t-.014-.146q0-.074.014-.146q.015-.073.043-.141t.069-.13q.041-.061.094-.113z");
}

</style>
