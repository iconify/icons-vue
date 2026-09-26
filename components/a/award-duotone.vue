<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="tjgol-bta"/><path class="y3qf9gidi"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:award-duotone" /></template>
<style>
.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.tjgol-bta {
  stroke-opacity: 0.4;
  d: path("M16.1787 14.6152L17.8979 19.9259C18.3406 21.1947 17.2603 22.4552 16.2597 21.8373L12.5365 19.5384C12.1988 19.3298 11.8012 19.3298 11.4635 19.5384L7.7403 21.8373C6.7397 22.4552 5.6594 21.1947 6.1021 19.9259L7.8213 14.6152");
}

.y3qf9gidi {
  fill: currentColor;
  d: path("M12 1C16.4183 1 20 4.58172 20 9C20 13.4183 16.4183 17 12 17C7.58172 17 4 13.4183 4 9C4 4.58172 7.58172 1 12 1Z");
  stroke: none;
}

</style>
