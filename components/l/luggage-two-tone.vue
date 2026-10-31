<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="u0iz5hn6v"/><path class="vo4dd1b0v"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:luggage-two-tone" /></template>
<style>
.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.u0iz5hn6v {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M7 5L17 5C18.6569 5 20 6.3431 20 8L20 18C20 19.6569 18.6569 21 17 21L7 21C5.3431 21 4 19.6569 4 18L4 8C4 6.3431 5.3431 5 7 5Z");
  stroke: none;
}

.vo4dd1b0v {
  d: path("M7 6L17 6C18.1046 6 19 6.8954 19 8L19 18C19 19.1046 18.1046 20 17 20L7 20C5.8954 20 5 19.1046 5 18L5 8C5 6.8954 5.8954 6 7 6ZM5 11L19 11M7 20L7 22M17 20L17 22M8 6L8.6213 3.5149C8.8439 2.6246 9.6438 2 10.5616 2L13.4384 2C14.3562 2 15.1561 2.6246 15.3787 3.5149L16 6");
}

</style>
