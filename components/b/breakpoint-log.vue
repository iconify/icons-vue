<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u0xz9o_0j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:breakpoint-log" /></template>
<style>
.u0xz9o_0j {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M5 2.75h14q1.346 0 2.298.952T22.25 6v8.5q0 3.25-3.25 3.25h-8.718l-3.788 3.314q-.112.099-.254.146q-.141.048-.29.038t-.282-.076q-.134-.066-.232-.178q-.09-.103-.138-.23q-.048-.128-.048-.264v-2.75H5q-3.25 0-3.25-3.25V6q0-1.346.952-2.298T5 2.75M7.5 7.5q-2.75 0-2.75 2.75T7.5 13t2.75-2.75T7.5 7.5m11 2h-6q-.074 0-.146.014q-.073.015-.141.043t-.13.069t-.113.094q-.053.052-.094.113t-.069.13t-.043.141t-.014.146t.014.146q.015.073.043.141t.069.13t.094.113q.052.053.113.094t.13.069t.141.043t.146.014h6q.074 0 .146-.014q.073-.015.141-.043t.13-.069q.061-.041.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146t-.014-.146q-.015-.073-.043-.141t-.069-.13t-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043T18.5 9.5");
}

</style>
