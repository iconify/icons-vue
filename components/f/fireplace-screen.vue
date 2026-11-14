<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="f3ul32h2e"/><path class="hrq_kkbtl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:fireplace-screen" /></template>
<style>
.f3ul32h2e {
  d: path("M3.5 21V11a8.5 8.5 0 0 1 17 0v10M7.25 9v12m9.5-12v12");
}

.hrq_kkbtl {
  d: path("M12 19.5c-2 0-2.25-2-1.75-3.25s1.5-2 1.75-4.25c1.25 1.5 2.25 3 2 5c-.25 1.75-1 2.5-2 2.5Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
