<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fvkod9bju"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:leaf-cannabis" /></template>
<style>
.fvkod9bju {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m11.125 12.25l-.77-2.86a1.5 1.5 0 0 1 0-.78l.77-2.86a.906.906 0 0 1 1.75 0l.77 2.86a1.5 1.5 0 0 1 0 .78l-.77 2.86a.906.906 0 0 1-1.75 0m2.404.988l1.289-1.907a1.5 1.5 0 0 1 .631-.529l2.102-.938a.78.78 0 0 1 .964 1.149l-1.289 1.906a1.5 1.5 0 0 1-.631.53l-2.102.938a.78.78 0 0 1-.964-1.149m-4.022 1.149l-2.102-.938a1.5 1.5 0 0 1-.631-.53l-1.289-1.906a.78.78 0 0 1 .964-1.149l2.102.938a1.5 1.5 0 0 1 .631.529l1.289 1.907a.78.78 0 0 1-.964 1.149m4.202.78l1.142-.223a1.5 1.5 0 0 1 1.061.187l.997.6a.67.67 0 0 1-.217 1.231l-1.142.223a1.5 1.5 0 0 1-1.061-.187l-.997-.6a.67.67 0 0 1 .217-1.231m-3.201 1.231l-.997.6a1.5 1.5 0 0 1-1.061.187l-1.142-.223a.67.67 0 0 1-.217-1.231l.997-.6a1.5 1.5 0 0 1 1.061-.187l1.142.223a.67.67 0 0 1 .217 1.231M12 15.5v6");
}

</style>
