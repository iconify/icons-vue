<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="df1svkbao"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:chhatri-sharp" /></template>
<style>
.df1svkbao {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 2.75v1.5M5.5 10a6.5 5.75 0 0 1 13 0Zm-2 0h17v2.5h-17zM6 12.5v6.25m4-6.25v6.25m4-6.25v6.25m4-6.25v6.25m-15 0h18v2.5H3z");
}

</style>
