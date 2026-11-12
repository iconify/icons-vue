<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="e0z-6ee1n"/><path class="qafvmubuv"/><path class="jyumk6b3q"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:kanban-linear" /></template>
<style>
.e0z-6ee1n {
  d: path("M12 12C11.0572 12 10.5858 12 10.2929 11.7071C10 11.4142 10 10.9428 10 10V4C10 3.05719 10 2.58579 10.2929 2.29289C10.5858 2 11.0572 2 12 2C12.9428 2 13.4142 2 13.7071 2.29289C14 2.58579 14 3.05719 14 4V10C14 10.9428 14 11.4142 13.7071 11.7071C13.4142 12 12.9428 12 12 12Z");
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jyumk6b3q {
  d: path("M19 19C18.0572 19 17.5858 19 17.2929 18.7071C17 18.4142 17 17.9428 17 17V4C17 3.05719 17 2.58579 17.2929 2.29289C17.5858 2 18.0572 2 19 2C19.9428 2 20.4142 2 20.7071 2.29289C21 2.58579 21 3.05719 21 4V17C21 17.9428 21 18.4142 20.7071 18.7071C20.4142 19 19.9428 19 19 19Z");
}

.qafvmubuv {
  d: path("M5 16C4.05719 16 3.58579 16 3.29289 15.7071C3 15.4142 3 14.9428 3 14V4C3 3.05719 3 2.58579 3.29289 2.29289C3.58579 2 4.05719 2 5 2C5.94281 2 6.41421 2 6.70711 2.29289C7 2.58579 7 3.05719 7 4V14C7 14.9428 7 15.4142 6.70711 15.7071C6.41421 16 5.94281 16 5 16Z");
}

</style>
