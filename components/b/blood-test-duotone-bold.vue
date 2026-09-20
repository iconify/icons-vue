<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="k5hu3qbal"/><path class="x2vm1eh6r"/><path class="va9i39bae"/><path class="j4a3yvbid"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:blood-test-duotone-bold" /></template>
<style>
.j4a3yvbid {
  d: path("m12 9 3 3a4 4 0 0 1 -6 0Z");
}

.k5hu3qbal {
  fill: currentColor;
  d: path("m12 9 3 3a4 4 0 0 1 -6 0Z");
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

.va9i39bae {
  d: path("M7 3h10");
}

.x2vm1eh6r {
  d: path("M9 3v15h6V3");
}

</style>
