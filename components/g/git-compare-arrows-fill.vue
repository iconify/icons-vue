<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="y5ms8l2it"/><path class="sxpj81bji"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:git-compare-arrows-fill" /></template>
<style>
.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.sxpj81bji {
  fill: currentColor;
  d: path("M10 6C10 8.20914 8.20914 10 6 10C3.79086 10 2 8.20914 2 6C2 3.79086 3.79086 2 6 2C8.20914 2 10 3.79086 10 6ZM22 18C22 15.7909 20.2091 14 18 14C15.7909 14 14 15.7909 14 18C14 20.2091 15.7909 22 18 22C20.2091 22 22 20.2091 22 18Z");
  stroke: none;
}

.y5ms8l2it {
  d: path("M6 9V16C6 17.1046 6.89543 18 8 18H10M14 6H16C17.1046 6 18 6.89543 18 8V15M14.7929 4L13.1465 5.64645C12.9512 5.84171 12.9512 6.15829 13.1465 6.35355L14.7929 8M9.2071 16L10.8535 17.6464C11.0488 17.8417 11.0488 18.1583 10.8535 18.3536L9.2071 20");
}

</style>
