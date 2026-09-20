<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ebovp7bpp"/><path class="nrm9lqn-q"/><path class="v-jogvb5z"/><path class="racsvxx3t"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:event-spike-duotone-thin" /></template>
<style>
.ebovp7bpp {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m10 6 -5 5h4l-5 5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.nrm9lqn-q {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M12 18h3l3 -3 3 3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.racsvxx3t {
  d: path("M12 18h3l3 -3 3 3");
}

.v-jogvb5z {
  d: path("m10 6 -5 5h4l-5 5");
}

</style>
