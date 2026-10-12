<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="vrh7tzbxf"/><path class="grksk5-iu"/><path class="jwm0iccwr"/><path class="o2w7ron4a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:bus-lane-sharp" /></template>
<style>
.grksk5-iu {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.25 5.5h9.5v5h-9.5z");
}

.jwm0iccwr {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M8 14.75h.01m7.99 0h.01");
}

.o2w7ron4a {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.75 18.25V21m8.5-2.75V21");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

.vrh7tzbxf {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.75 2.75h14.5v15.5H4.75z");
}

</style>
