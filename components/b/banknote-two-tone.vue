<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="ta7j8suqy"/><path class="n7cc2rm8i"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:banknote-two-tone" /></template>
<style>
.n7cc2rm8i {
  d: path("M22 17L22 7C22 5.8954 21.1046 5 20 5L4 5C2.8954 5 2 5.8954 2 7L2 17C2 18.1046 2.8954 19 4 19L20 19C21.1046 19 22 18.1046 22 17ZM14 12C14 13.1046 13.1046 14 12 14C10.8954 14 10 13.1046 10 12C10 10.8954 10.8954 10 12 10C13.1046 10 14 10.8954 14 12ZM17 9L18 9M7 15L6 15");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.ta7j8suqy {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M23 17L23 7C23 5.3431 21.6569 4 20 4L4 4C2.3431 4 1 5.3431 1 7L1 17C1 18.6569 2.3431 20 4 20L20 20C21.6569 20 23 18.6569 23 17Z");
  stroke: none;
}

</style>
