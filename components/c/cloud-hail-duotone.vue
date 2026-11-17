<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="pwag89bfc"/><path class="h0bsrevjc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:cloud-hail-duotone" /></template>
<style>
.h0bsrevjc {
  fill: currentColor;
  d: path("M13.5 17.5C13.5 18.328 12.8284 19 12 19C11.1716 19 10.5 18.328 10.5 17.5C10.5 16.672 11.1716 16 12 16C12.8284 16 13.5 16.672 13.5 17.5ZM8.5 20.5C8.5 21.328 7.8284 22 7 22C6.1716 22 5.5 21.328 5.5 20.5C5.5 19.672 6.1716 19 7 19C7.8284 19 8.5 19.672 8.5 20.5ZM18.5 20.5C18.5 21.328 17.8284 22 17 22C16.1716 22 15.5 21.328 15.5 20.5C15.5 19.672 16.1716 19 17 19C17.8284 19 18.5 19.672 18.5 20.5Z");
  stroke: none;
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.pwag89bfc {
  stroke-opacity: 0.4;
  d: path("M4 16.464C2.7624 15.75 2 14.429 2 13C2 10.791 3.7909 9 6 9C6 5.686 8.6863 3 12 3C15.3137 3 18 5.686 18 9C20.2091 9 22 10.791 22 13C22 14.429 21.2376 15.75 20 16.464");
}

</style>
