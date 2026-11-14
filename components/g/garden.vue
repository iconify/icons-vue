<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sfanvxall"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:garden" /></template>
<style>
.sfanvxall {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 21.5h19M4.25 9v2.5a1.75 1.75 0 0 0 3.5 0V9l-1 1.25L6 9l-.75 1.25Zm6-4v2.5a1.75 1.75 0 0 0 3.5 0V5l-1 1.25L12 5l-.75 1.25Zm6 3v2.5a1.75 1.75 0 0 0 3.5 0V8l-1 1.25L18 8l-.75 1.25ZM6 13.25v8.25m6-12.25V21.5m6-9.25v9.25M12 17c-2 0-3-1.5-3-3c1.75 0 3 1.25 3 3");
}

</style>
