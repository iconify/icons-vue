<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q5l9jyb0x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:distillation-sharp" /></template>
<style>
.q5l9jyb0x {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.75 3.75h17.5l-.71.71l-5.83 5.83L14 11v2.25h-4V11l-.71-.71l-5.83-5.83l-.71-.71zM6.5 7h11M12 15.5c1.4 1.5 2.1 2.6 2.1 3.4a2.1 2.1 0 0 1-4.2 0c0-.8.7-1.9 2.1-3.4Z");
}

</style>
