<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m0kt18bov"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:electricity" /></template>
<style>
.m0kt18bov {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M13.422 2.022q.065-.078.148-.136t.179-.093t.197-.041t.201.013q.073.014.141.042t.129.07q.062.041.114.093q.052.053.093.114t.069.13t.043.14q.014.073.014.147t-.015.146l-1.32 6.603H19.5q.131 0 .254.044t.224.128q.057.047.103.104q.047.057.082.123q.034.065.055.136q.022.07.029.144t-.001.147q-.007.073-.029.144t-.057.136t-.082.122l-9.5 11.5q-.065.078-.148.136t-.179.093q-.096.034-.197.041t-.201-.013q-.073-.014-.141-.042t-.129-.07t-.114-.093q-.052-.053-.093-.114t-.069-.13t-.043-.14q-.014-.073-.014-.147t.015-.146l1.32-6.603H4.5q-.131 0-.254-.044q-.123-.045-.224-.128q-.057-.047-.103-.104q-.047-.057-.082-.123q-.034-.065-.055-.136q-.022-.07-.029-.144t.001-.147t.029-.144t.057-.136t.082-.122z");
}

</style>
