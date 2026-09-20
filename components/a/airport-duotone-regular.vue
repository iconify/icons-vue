<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="w-o_3soud"/><path class="fbzl9tb4p"/><path class="fnbgpcbhf"/><path class="yomj0bbqc"/><path class="ay19-ob6x"/><path class="bos0j4biy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:airport-duotone-regular" /></template>
<style>
.ay19-ob6x {
  d: path("m6 9 4.5 -4.5h3L18 9");
}

.bos0j4biy {
  d: path("M3 21h18");
}

.fbzl9tb4p {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m6 9 4.5 -4.5h3L18 9");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.fnbgpcbhf {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M3 21h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.w-o_3soud {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M9 21V9h6v12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.yomj0bbqc {
  d: path("M9 21V9h6v12");
}

</style>
