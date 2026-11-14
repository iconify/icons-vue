<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="rw52jubvw"/><path class="d5xlclvji"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:book-press" /></template>
<style>
.d5xlclvji {
  d: path("M7.5 14h9v3h-9Z");
}

.rw52jubvw {
  d: path("M3 20.5h18m-16.5 0V7h15v13.5M12 3v11M8.5 3h7");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
