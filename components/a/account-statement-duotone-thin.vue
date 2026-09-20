<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="b7uyqxwtl"/><path class="xsv2fybbr"/><path class="aunvmia-t"/><path class="rs-eeii7j"/><path class="ky4omnbla"/><path class="zwh7a2bjz"/><path class="hsbav3b9a"/><path class="jm6ti-b3r"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:account-statement-duotone-thin" /></template>
<style>
.aunvmia-t {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M6 12h9");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.b7uyqxwtl {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M4 5h14l4 4v8a2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2V7a2 2 0 0 1 2 -2m14 0v4h4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.hsbav3b9a {
  d: path("M6 12h9");
}

.jm6ti-b3r {
  d: path("M6 15h12");
}

.ky4omnbla {
  d: path("M4 5h14l4 4v8a2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2V7a2 2 0 0 1 2 -2m14 0v4h4");
}

.rs-eeii7j {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M6 15h12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.xsv2fybbr {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M6 9h9");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.zwh7a2bjz {
  d: path("M6 9h9");
}

</style>
