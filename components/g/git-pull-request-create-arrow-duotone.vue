<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="pi6c9vaae"/><path class="cwtsvfbtg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:git-pull-request-create-arrow-duotone" /></template>
<style>
.cwtsvfbtg {
  d: path("M6 21L6 9M14 6L16 6C17.1046 6 18 6.8954 18 8L18 12M14.7929 4L13.1465 5.6465C12.9512 5.8417 12.9512 6.1583 13.1465 6.3536L14.7929 8M18.5 16L18.5 21M16 18.5L21 18.5");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.pi6c9vaae {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M10 6C10 8.20914 8.20914 10 6 10C3.79086 10 2 8.20914 2 6C2 3.79086 3.79086 2 6 2C8.20914 2 10 3.79086 10 6Z");
  stroke: none;
}

</style>
