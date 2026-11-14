<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="al8ocebza"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:bats-flock" /></template>
<style>
.al8ocebza {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12.182 11.345c-.522.402-1.102 1.092-1.682 2.155c-1.5-2.75-3-3-3.5-2.25c-.5-1-2-1.25-3-.25c-.5-1-1.5-3.5-1.5-7q3 2.25 6 3l.75-2.5l.5 2h1.5l.5-2L12.5 7q3-.75 6-3c0 3.5-1 6-1.5 7c-1-1-2.5-.75-3 .25c-.213-.319-.606-.457-1.103-.299M15 16c1 .75 2 1 3 1l.5-1l.5 1c1 0 2-.25 3-1c0 2-.75 3.5-1.25 3.75c-.5-.5-1.25-.5-1.5 0L18.5 21l-.75-1.25c-.25-.5-1-.5-1.5 0C15.75 19.5 15 18 15 16Z");
}

</style>
