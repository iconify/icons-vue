<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="msm687bgx"/><path class="v__0ng79y"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:fire-emoji-sharp" /></template>
<style>
.msm687bgx {
  d: path("M12 21.25a7 7 0 0 1-7-7c0-2.75.75-4.75 1.5-6.75l.726 2.54L9 10.75c0-3 1-5.75 3-8C14 5 15 7.25 15 10c1-.75 1.75-2 2.5-3.5c1 2 1.5 4.75 1.5 7.75a7 7 0 0 1-7 7Z");
}

.v__0ng79y {
  d: path("M12 19H9.75v-2.25c0-1.5 1-2.75 2.25-4.25c1.25 1.5 2.25 2.75 2.25 4.25V19z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
