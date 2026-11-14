<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="t1b2ohb9n"/><path class="e7s618bol"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:csr" /></template>
<style>
.e7s618bol {
  d: path("M2.5 21h10l7-4.5a1.5 1.5 0 0 0-1.75-2.25l-4 2.5");
}

.t1b2ohb9n {
  d: path("M12 11C9 9 6.5 7 6.5 4.75c0-1.75 1.25-2.5 2.75-2.5C10.5 2.25 11.5 3 12 4c.5-1 1.5-1.75 2.75-1.75c1.5 0 2.75.75 2.75 2.5C17.5 7 15 9 12 11Zm-9.5 4.5h4c1.5 0 2.5 1 3.5 1h3a1.25 1.25 0 0 1 0 2.5H9.5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
