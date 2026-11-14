<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="wnruagb8u"/><path class="hh7r6kkqe"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:esim-download" /></template>
<style>
.hh7r6kkqe {
  d: path("M8.5 14.5h7v4h-7Zm3.5-9v6M9.5 9l2.5 2.5L14.5 9");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.wnruagb8u {
  d: path("M4.5 4.5a2 2 0 0 1 2-2H14L19.5 8v11.5a2 2 0 0 1-2 2h-11a2 2 0 0 1-2-2Z");
}

</style>
