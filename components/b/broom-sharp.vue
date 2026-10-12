<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dqwh8pm5t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:broom-sharp" /></template>
<style>
.dqwh8pm5t {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 2.75v7m-2.75 0h5.5l.909-.005l.091.905l.25 2.6l2.15 6.65l.512 1.369l-1.462-.019H6.8l-1.462.019l.512-1.369L8 13.25l.25-2.6l.091-.905zM8 13.25h8m-5.5 8v-4m3 4v-4");
}

</style>
