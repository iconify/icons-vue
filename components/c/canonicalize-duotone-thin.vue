<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="owzsyobbh"/><path class="zhzzk2fcp"/><path class="cf-dqybgk"/><path class="oboujbbaa"/><path class="rdidnh2az"/><path class="ok9ioqb8x"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:canonicalize-duotone-thin" /></template>
<style>
.cf-dqybgk {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M4 17h16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.oboujbbaa {
  d: path("m3 5 3 3 3 -3 3 3 3 -3");
}

.ok9ioqb8x {
  d: path("M4 17h16");
}

.owzsyobbh {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m3 5 3 3 3 -3 3 3 3 -3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.rdidnh2az {
  d: path("m10 11.5 2 2 2 -2");
}

.zhzzk2fcp {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m10 11.5 2 2 2 -2");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
