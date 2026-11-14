<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c9tf3c6um"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:blister-pack-grocery" /></template>
<style>
.c9tf3c6um {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M13 9.75h-1.5V7q0-2.75-2.75-2.75T6 7v2.75q-.104 0-.205.029q-.1.028-.189.083t-.16.132t-.117.171l-3.5 7q-.079.158-.079.335q0 .074.014.146q.015.073.043.141t.069.13q.041.061.094.113q.052.053.113.094t.13.069t.141.043t.146.014H18q.104 0 .205-.029q.1-.028.189-.083t.16-.132q.07-.077.117-.171l3.5-7q.079-.158.079-.335q0-.074-.014-.146q-.015-.073-.043-.141t-.069-.13t-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043t-.146-.014h-3V7q0-2.75-2.75-2.75T13 7zm1.5 0H17V7q0-1.25-1.25-1.25T14.5 7zM10 7v2.75H7.5V7q0-1.25 1.25-1.25T10 7");
}

</style>
