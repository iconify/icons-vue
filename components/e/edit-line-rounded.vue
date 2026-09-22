<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vy-so3b7m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:edit-line-rounded" /></template>
<style>
.vy-so3b7m {
  fill: currentColor;
  d: path("m9.896 20l1-1H20.5q.213 0 .356.144t.144.357t-.144.356T20.5 20zm7.608-12.411L19 6.111L17.889 5l-1.477 1.496zM4 19.191v-1.04q0-.332.13-.632t.349-.518L17.18 4.287q.153-.137.339-.212T17.907 4t.39.064t.35.228l1.067 1.074q.159.165.223.35q.063.187.063.379q0 .205-.068.39q-.069.186-.218.34L6.998 19.521q-.217.218-.518.348T5.848 20h-1.04q-.344 0-.576-.232T4 19.192");
}

</style>
