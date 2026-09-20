<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ccfz103ff"/><path class="b2n5wjbvh"/><path class="o1dsref5n"/><path class="ae0h5kb0o"/><path class="x3sflacnk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:attic-outline-thin" /></template>
<style>
.ae0h5kb0o {
  d: path("M9 15h6");
}

.b2n5wjbvh {
  d: path("M9 12v9");
}

.ccfz103ff {
  d: path("M2 12 12 2l10 10Z");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.o1dsref5n {
  d: path("M15 12v9");
}

.x3sflacnk {
  d: path("M9 18h6");
}

</style>
