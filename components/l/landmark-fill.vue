<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="w_8awuckf"/><path class="c60pdqbsy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:landmark-fill" /></template>
<style>
.c60pdqbsy {
  d: path("M6 12L6 17M12 12L12 17M18 12L18 17M3 21L21 21");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.w_8awuckf {
  fill: currentColor;
  d: path("M2.8392 6.1534C2.3253 6.4053 1.9996 6.9278 1.9996 7.5001C1.9996 8.3286 2.6714 9.0002 3.4999 9L20.5 9C21.3286 9.0002 22.0004 8.3286 22.0004 7.5001C22.0004 6.9278 21.6747 6.4053 21.1608 6.1534L13.3215 2.3067C12.9102 2.1049 12.4582 1.9999 12 1.9999C11.5418 1.9999 11.0898 2.1049 10.6785 2.3067L2.8392 6.1534Z");
  stroke: none;
}

</style>
