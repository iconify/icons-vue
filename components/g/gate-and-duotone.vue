<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="nvktyhweu"/><path class="snoarnpfi"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:gate-and-duotone" /></template>
<style>
.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.nvktyhweu {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M16.6569 6.3431C18.1035 7.7898 19 9.7911 19 12C19 16.4183 15.4183 20 11 20L9 20C7.3431 20 6 18.6569 6 17L6 7C6 5.3431 7.3431 4 9 4L11 4C13.2089 4 15.2102 4.8965 16.6569 6.3431Z");
  stroke: none;
}

.snoarnpfi {
  d: path("M2 8L7 8M2 16L7 16M18 12L22 12");
}

</style>
