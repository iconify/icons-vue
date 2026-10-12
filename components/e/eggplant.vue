<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="q159txfot"/><path class="ja-dn8b8f"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:eggplant" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ja-dn8b8f {
  d: path("M12.75 8.25c.5-2 2.25-3.25 4.25-3c.25 2-1 3.75-3 4.25m3-4.25L19.25 3");
}

.q159txfot {
  d: path("M14.5 7.5c2 1.25 2.5 3.5 1.75 5.75c-1.25 3.75-4 6.5-7.5 7.5c-2.75.75-5-1-5-3.5c0-2 1.25-3.25 3-4.5c2-1.5 3.25-3 4.25-4.5c.75-1.25 2-1.75 3.5-.75");
}

</style>
