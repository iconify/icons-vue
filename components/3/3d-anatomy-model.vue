<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="nnpq78bkt"/><path class="tsm53-xwj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:3d-anatomy-model" /></template>
<style>
.nnpq78bkt {
  d: path("M11.733 14.5H4.25c0-3 2.25-4.75 5-4.75c2.104 0 3.915 1.024 4.65 2.849m-2.228 8.917c-.697.153-1.519.234-2.422.234c-2.75 0-4.75-.75-4.75-2V19c0-1.25 2-2 4.75-2c.543 0 1.057.029 1.532.086M6.75 5a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0Zm2.5 9.5V17M18 14.25L21.5 16v4L18 21.75L14.5 20v-4Z");
}

.tsm53-xwj {
  d: path("m14.5 16l3.5 1.75L21.5 16M18 17.75v4");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
