<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="jvhzyj__t"/><path class="iuxdx2vhv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:calendar-user" /></template>
<style>
.iuxdx2vhv {
  d: path("M16.25 15.5a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0ZM15 21c0-1.75 1.25-2.5 3-2.5s3 .75 3 2.5Z");
}

.jvhzyj__t {
  d: path("M12.2 20.5H3.5V5h17v6.7M8 3v4m8-4v4M3.5 10h17M8 3v4m8-4v4M3.5 10h17");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
