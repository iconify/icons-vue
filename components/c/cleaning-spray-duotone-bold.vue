<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="wp-77vaaw"/><path class="s8xlo1b-n"/><path class="role8-fry"/><path class="f8ggyj7xo"/><path class="ht122hbxe"/><path class="wvj5idbgl"/><path class="fn3ujkbay"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:cleaning-spray-duotone-bold" /></template>
<style>
.f8ggyj7xo {
  d: path("M7 10v11h8V10Z");
}

.fn3ujkbay {
  d: path("M19 7a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.ht122hbxe {
  d: path("M9 10V5h6v3");
}

.role8-fry {
  fill: currentColor;
  d: path("M19 7a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.s8xlo1b-n {
  fill: currentColor;
  d: path("M17 4a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.wp-77vaaw {
  fill: currentColor;
  d: path("M7 10v11h8V10Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.wvj5idbgl {
  d: path("M17 4a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

</style>
