<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="rnzh-pbqy"/><path clip-rule="evenodd" class="mq6c8ib1c"/><path class="wggdajp-t"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:circuit-board-duotone" /></template>
<style>
.mq6c8ib1c {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M10 5H13C14.1046 5 15 5.895 15 7V12C15 13.105 14.1046 14 13 14H7C5.8954 14 5 13.105 5 12V7C5 5.895 5.8954 5 7 5H10ZM6 17H10C10.5523 17 11 17.448 11 18C11 18.552 10.5523 19 10 19H6C5.4477 19 5 18.552 5 18C5 17.448 5.4477 17 6 17ZM15 18C15 18.552 14.5523 19 14 19C13.4477 19 13 18.552 13 18C13 17.448 13.4477 17 14 17C14.5523 17 15 17.448 15 18Z");
  stroke: none;
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.rnzh-pbqy {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M19 12V19C19 21.209 17.2092 23 15 23H5C2.7908 23 1 21.209 1 19V5C1 2.791 2.7908 1 5 1H15C17.2092 1 19 2.791 19 5V12Z");
  stroke: none;
}

.wggdajp-t {
  d: path("M18 7H22M18 12H22M18 17H22");
}

</style>
