<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="z8uuk02yn"/><path class="uzbtycc2z"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:dice-d10-duotone" /></template>
<style>
.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.uzbtycc2z {
  d: path("M10.5858 2.5858C10.9609 2.2107 11.4696 2 12 2C12.5304 2 13.0391 2.2107 13.4142 2.5858L21.4142 10.5858C21.7893 10.9609 22 11.4696 22 12C22 12.5304 21.7893 13.0391 21.4142 13.4142L13.4142 21.4142C13.0391 21.7893 12.5304 22 12 22C11.4696 22 10.9609 21.7893 10.5858 21.4142L2.5858 13.4142C2.2107 13.0391 2 12.5304 2 12C2 11.4696 2.2107 10.9609 2.5858 10.5858L10.5858 2.5858ZM8 12L12 2L16 12L12 16Z");
}

.z8uuk02yn {
  stroke-opacity: 0.4;
  d: path("M2 12L8 12M16 12L22 12M12 16L12 22");
}

</style>
