<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="b6uonebog"/><path class="l_j0jz7_x"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:circle-square-dashed-fill" /></template>
<style>
.b6uonebog {
  fill: currentColor;
  d: path("M17 9C17 13.4183 13.4183 17 9 17C4.5817 17 1 13.4183 1 9C1 4.5817 4.5817 1 9 1C13.4183 1 17 4.5817 17 9Z");
  stroke: none;
}

.l_j0jz7_x {
  d: path("M20 9C21.1046 9 22 9.8954 22 11M22 15V16M22 20C22 21.1046 21.1046 22 20 22M16 22H15M11 22C9.8954 22 9 21.1046 9 20");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
