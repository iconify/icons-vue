<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="p8bj2jw6u"/><path class="ciiu89bvh"/><path class="fk-snpvfc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:braided-cord" /></template>
<style>
.ciiu89bvh {
  d: path("M7.75 3C7.25 5 9.5 6.5 12 7c6.5.75 6.5 5.25 0 6s-6.5 5.25 0 6c2.5.5 4.25 1 4.25 2");
}

.fk-snpvfc {
  d: path("M16.25 3c-.75 1.25-2.5 1.75-4.25 2c-6.5.75-6.5 5.25 0 6s6.5 5.25 0 6c-3.5.5-4.25 2-4.25 4");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.p8bj2jw6u {
  d: path("M12 3c6.5.75 6.5 5.25 0 6s-6.5 5.25 0 6s6.5 5.25 0 6");
}

</style>
