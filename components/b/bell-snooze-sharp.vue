<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qopwa6b7c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:bell-snooze-sharp" /></template>
<style>
.qopwa6b7c {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 3.25a6 6 0 0 0-6 6v4.694l-.7.856l-.6.75l-1.56 1.95h17.72l-1.56-1.95l-.6-.75l-.7-.856V9.25a6 6 0 0 0-6-6Zm-2.25 17l.871.95h2.758l.871-.95");
}

</style>
