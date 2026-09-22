<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="imromncwr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:edit-line-outline-rounded" /></template>
<style>
.imromncwr {
  fill: currentColor;
  d: path("m9.896 20l1-1H20.5q.213 0 .356.144t.144.357t-.144.356T20.5 20zM5 19h1.098L16.796 8.302l-1.098-1.098L5 17.902zM19.02 6.092l-1.112-1.111zm-2.782 1.67l-.54-.558l1.098 1.098zM4 19.193v-1.04q0-.332.13-.632t.349-.518L17.18 4.287q.153-.137.339-.212T17.907 4t.39.064t.35.228l1.067 1.074q.159.165.223.35q.063.187.063.379q0 .205-.068.39q-.069.186-.218.34L6.998 19.521q-.217.218-.518.348T5.848 20h-1.04q-.344 0-.576-.232T4 19.192");
}

</style>
