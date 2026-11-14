<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="alcx7jb-b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:camp-host" /></template>
<style>
.alcx7jb-b {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12.372 20.5H4c-.6 0-1-.4-1-1c0-3.25 3.25-5.5 7.5-5.5c1.801 0 3.422.404 4.692 1.117M6.5 7a4 4 0 1 0 8 0a4 4 0 1 0-8 0ZM15 21.5l3.25-6.25l3.25 6.25m-3.25-6.25v6.25");
}

</style>
