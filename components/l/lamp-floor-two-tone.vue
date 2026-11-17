<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="yq6m31a4y"/><path class="k38k2p69h"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:lamp-floor-two-tone" /></template>
<style>
.k38k2p69h {
  d: path("M12 12V22M9 22H15M9.712 2.503C9.8901 2.192 10.2213 2 10.5799 2H13.4201C13.7787 2 14.1099 2.192 14.288 2.503L18.8664 10.503C19.248 11.17 18.7666 12 17.9985 12H6.0015C5.2334 12 4.752 11.17 5.1336 10.503L9.712 2.503Z");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.yq6m31a4y {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M13.4199 1C14.137 1 14.8 1.384 15.1562 2.007L19.7344 10.007C20.4973 11.34 19.534 13 17.998 13H6.0019C4.4659 13 3.5026 11.34 4.2656 10.007L8.8437 2.007C9.2 1.384 9.8629 1 10.5801 1H13.4199Z");
  stroke: none;
}

</style>
