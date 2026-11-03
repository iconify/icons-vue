<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="kovoczotl"/><path class="asx9dyqwg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:earbuds-off" /></template>
<style>
.asx9dyqwg {
  fill: currentColor;
  d: path("M19 7C19 7.5523 18.5523 8 18 8C17.4477 8 17 7.5523 17 7C17 6.4477 17.4477 6 18 6C18.5523 6 19 6.4477 19 7Z");
  stroke: none;
}

.kovoczotl {
  d: path("M3.7159 3.7159C2.6787 4.4386 2 5.6401 2 7C2 8.9008 3.3376 10.539 5.2 10.9192C5.6656 11.0142 6 11.4238 6 11.899L6 19C6 20.1046 6.8954 21 8 21C9.1046 21 10 20.1046 10 19L10 10M14 14L14 19C14 20.1046 14.8954 21 16 21C17.1046 21 18 20.1046 18 19L18 18M6 17L10 17M14 17L17 17M18 12.3431L18 11.899C18 11.4238 18.3344 11.0142 18.8 10.9192C20.6624 10.539 22 8.9008 22 7C22 4.7909 20.2091 3 18 3C15.7909 3 14 4.7909 14 7L14 8.3431M2 2L22 22");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
