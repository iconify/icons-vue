<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="b281jacjk"/><path class="ohpt09bzf"/><path class="mtc3mjb7f"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:coach" /></template>
<style>
.b281jacjk {
  d: path("M9 4H6.5a2 2 0 0 0-2 2v13.5a2 2 0 0 0 2 2h11a2 2 0 0 0 2-2V6a2 2 0 0 0-2-2H15");
}

.mtc3mjb7f {
  d: path("M14.25 13.25L16 11.5l1.75 1.75");
}

.ohpt09bzf {
  d: path("M9 2.5h6V6H9Zm-1.25 14a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0ZM14 18c1.5 0 2-2 2-6.5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
