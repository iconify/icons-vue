<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="rbsu0tb-j"/><path class="dhvo-qnpk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:kids-pool" /></template>
<style>
.dhvo-qnpk {
  d: path("M12.5 8a2 2 0 1 0 4 0a2 2 0 1 0-4 0Zm-9 5.25V5.5a1.75 1.75 0 0 1 3.5 0");
}

.rbsu0tb-j {
  d: path("M9.5 8a5 5 0 1 0 10 0a5 5 0 1 0-10 0Zm-7 9q2.375-1.5 4.75 0T12 17t4.75 0t4.75 0m-19 4q2.375-1.5 4.75 0T12 21t4.75 0t4.75 0");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
