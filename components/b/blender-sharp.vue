<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="wyqp7bb0k"/><path class="wr6i3lb3h"/><path class="z_b3_fbbi"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:blender-sharp" /></template>
<style>
.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

.wr6i3lb3h {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m9.5 10.75l2.5-1.5l2.5 1.5M7 16.5h10v4.75H7z");
}

.wyqp7bb0k {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.5 2.75h10.25l-.19 1.24l-1.37 8.77L16 14H8l-.19-1.24l-1.37-8.77l-.19-1.24z");
}

.z_b3_fbbi {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 18.88h.01");
}

</style>
