<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="nqh-8w1pp"/><path class="voo1uhrxq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:cpu-fill" /></template>
<style>
.nqh-8w1pp {
  fill: currentColor;
  d: path("M7 3L17 3C19.2091 3 21 4.7909 21 7L21 17C21 19.2091 19.2091 21 17 21L7 21C4.7909 21 3 19.2091 3 17L3 7C3 4.7909 4.7909 3 7 3ZM9 7C7.8954 7 7 7.8954 7 9L7 15C7 16.1046 7.8954 17 9 17L15 17C16.1046 17 17 16.1046 17 15L17 9C17 7.8954 16.1046 7 15 7L9 7Z");
  stroke: none;
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.voo1uhrxq {
  d: path("M9 4L9 2M9 20L9 22M4 9L2 9M20 9L22 9M15 4L15 2M15 20L15 22M4 15L2 15M20 15L22 15");
}

</style>
