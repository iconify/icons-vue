<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fbiinjsub"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:host-mc" /></template>
<style>
.fbiinjsub {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M5.75 7q0-1.968 1.391-3.359T10.5 2.25t3.359 1.391T15.25 7t-1.391 3.359T10.5 11.75t-3.359-1.391T5.75 7m10.75.5q0-2.75 2.75-2.75T22 7.5q0 2.477-2.231 2.723l-1.323 3.306q-.027.068-.067.13t-.092.115t-.113.094t-.129.071q-.067.029-.14.045q-.072.015-.146.016t-.146-.013q-.073-.013-.142-.041q-.068-.027-.13-.067t-.115-.092t-.094-.113q-.042-.061-.071-.129q-.029-.067-.045-.14q-.015-.072-.016-.146t.013-.146t.041-.142l1.139-2.849Q16.5 9.658 16.5 7.5M4.718 14.923Q2.25 16.702 2.25 19.5q0 1.75 1.75 1.75h13q1.75 0 1.75-1.75q0-2.798-2.468-4.577q-2.32-1.673-5.782-1.673t-5.782 1.673");
}

</style>
