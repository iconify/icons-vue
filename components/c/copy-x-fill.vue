<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="t0d5-tp3g"/><path clip-rule="evenodd" class="sona08b8s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:copy-x-fill" /></template>
<style>
.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.sona08b8s {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M11 7L19 7C21.2091 7 23 8.7909 23 11L23 19C23 21.2091 21.2091 23 19 23L11 23C8.7909 23 7 21.2091 7 19L7 11C7 8.7909 8.7909 7 11 7ZM16.4142 15L18.7071 12.7071C18.8946 12.5196 19 12.2652 19 12C19 11.4477 18.5523 11 18 11C17.7348 11 17.4804 11.1054 17.2929 11.2929L15 13.5858L12.7071 11.2929C12.5196 11.1054 12.2652 11 12 11C11.4477 11 11 11.4477 11 12C11 12.2652 11.1054 12.5196 11.2929 12.7071L13.5858 15L11.2929 17.2929C11.1054 17.4804 11 17.7348 11 18C11 18.5523 11.4477 19 12 19C12.2652 19 12.5196 18.8946 12.7071 18.7071L15 16.4142L17.2929 18.7071C17.4804 18.8946 17.7348 19 18 19C18.5523 19 19 18.5523 19 18C19 17.7348 18.8946 17.4804 18.7071 17.2929L16.4142 15Z");
  stroke: none;
}

.t0d5-tp3g {
  d: path("M15.8284 4C15.4046 2.8015 14.2714 2 13 2L5 2C3.3432 2 2 3.3432 2 5L2 13C2 14.2714 2.8015 15.4046 4 15.8284");
}

</style>
