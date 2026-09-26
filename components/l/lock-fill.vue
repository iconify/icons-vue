<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="smi4ruzkp"/><path clip-rule="evenodd" class="gluuty0cs"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:lock-fill" /></template>
<style>
.gluuty0cs {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M17 9C19.2091 9 21 10.7909 21 13V19C21 21.2091 19.2091 23 17 23H7C4.79086 23 3 21.2091 3 19V13C3 10.7909 4.79086 9 7 9H17ZM12 14.5C11.1716 14.5 10.5 15.1716 10.5 16C10.5 16.8284 11.1716 17.5 12 17.5C12.8284 17.5 13.5 16.8284 13.5 16C13.5 15.1716 12.8284 14.5 12 14.5Z");
  stroke: none;
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.smi4ruzkp {
  d: path("M7.5 10V6.5C7.5 4.01472 9.51472 2 12 2C14.4853 2 16.5 4.01472 16.5 6.5V10");
}

</style>
