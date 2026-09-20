<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="sqwo1bbye"/><path class="grtatgbqk"/><path class="v90e5qb-m"/><path class="v-jogvb5z"/><path class="weeetziwb"/><path class="qydoy8byr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:event-failed-duotone-regular" /></template>
<style>
.grtatgbqk {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m14 10 5 5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.qydoy8byr {
  d: path("m19 10 -5 5");
}

.sqwo1bbye {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m10 6 -5 5h4l-5 5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.v-jogvb5z {
  d: path("m10 6 -5 5h4l-5 5");
}

.v90e5qb-m {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m19 10 -5 5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.weeetziwb {
  d: path("m14 10 5 5");
}

</style>
