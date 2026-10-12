<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="e4m92bcnp"/><path class="vk-_sh12h"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:hammer" /></template>
<style>
.e4m92bcnp {
  d: path("m11.12 3.5l.23.02q1.24.16 2.12 1.04l6.9 6.9q.88.88 0 1.76l-1.97 1.97q-.88.88-1.76 0L9.74 8.3q-.88-.88-1.04-2.12l-.02-.24q-.16-1.24.52-1.92t1.92-.52");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.vk-_sh12h {
  d: path("m12.3 10.85l.25.26q1.06 1.06 0 2.12L6.19 19.6q-1.06 1.06-2.12 0l-.26-.26q-1.06-1.06 0-2.12l6.37-6.37q1.06-1.06 2.12 0");
}

</style>
