<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="v8ep90fvj"/><path class="xvjmi7w8l"/><path class="hk57ajm5r"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:campus-hiring" /></template>
<style>
.hk57ajm5r {
  d: path("M12 13.75v1.75h1.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.v8ep90fvj {
  d: path("M6 21.5v-10L12 7l6 4.5v10ZM12 7V2m1.213.303l1.287.322a.644.644 0 0 1 0 1.25l-1.287.322A.976.976 0 0 1 12 3.25a.976.976 0 0 1 1.213-.947");
}

.xvjmi7w8l {
  d: path("M8.75 15.5a3.25 3.25 0 1 0 6.5 0a3.25 3.25 0 1 0-6.5 0");
}

</style>
