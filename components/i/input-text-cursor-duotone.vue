<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="af4gihwie"/><path class="unyhsvb3l"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:input-text-cursor-duotone" /></template>
<style>
.af4gihwie {
  stroke-opacity: 0.4;
  d: path("M12 7L4 7C2.8954 7 2 7.8954 2 9L2 15C2 16.1046 2.8954 17 4 17L12 17M20 7C21.1046 7 22 7.8954 22 9L22 15C22 16.1046 21.1046 17 20 17");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.unyhsvb3l {
  d: path("M6 11L6 13M16 4.25C15.5556 3.6875 14.1333 2 12 2M16 4.25C16.4444 3.6875 17.8667 2 20 2M16 4.25L16 19.75M16 19.75C16.4444 20.3125 17.8667 22 20 22M16 19.75C15.5556 20.3125 14.1333 22 12 22");
}

</style>
