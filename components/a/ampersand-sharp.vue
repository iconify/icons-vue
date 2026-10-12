<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u7y39dbug"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:ampersand-sharp" /></template>
<style>
.u7y39dbug {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m19.5 20.25l-10.75-11L7 7.5V3.25h5.5V6c0 1.75-1.5 2.75-4 4.25c-2.25 1.25-3.75 2.75-3.75 5c0 2.5 2 4.75 4.75 4.75c3 0 5.75-2 7.5-5.75");
}

</style>
