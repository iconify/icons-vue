<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="egysv6xjd"/><path class="fzx37jvtc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:alien-face-sharp" /></template>
<style>
.egysv6xjd {
  d: path("M12 5c4.1 0 7.25 2.75 7.25 6.5c0 4.5-4.1 9.75-7.25 9.75S4.75 16 4.75 11.5C4.75 7.75 7.9 5 12 5Zm-2.75.4L7.5 3m7.25 2.4L16.5 3");
}

.fzx37jvtc {
  d: path("M7.5 10.5c1.5 0 3 1 3 2.5c-1.5 0-3-1-3-2.5Zm9 0c-1.5 0-3 1-3 2.5c1.5 0 3-1 3-2.5ZM11 17h2");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
