<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<g class="cuyn6tgcc"><path class="d-lzeh97n"/><path class="c424ysbwk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:circuitry-duotone" /></template>
<style>
.c424ysbwk {
  d: path("M208 32H48a16 16 0 0 0-16 16v160a16 16 0 0 0 16 16h160a16 16 0 0 0 16-16V48a16 16 0 0 0-16-16M88 160a8 8 0 1 1-8 8a8 8 0 0 1 8-8M48 48h32v97.38a24 24 0 1 0 16 0v-30.07l48 48V208H48Zm160 160h-48v-48a8 8 0 0 0-2.34-5.66L96 92.69V48h32v24a8 8 0 0 0 2.34 5.66l16 16A23.74 23.74 0 0 0 144 104a24 24 0 1 0 24-24a23.74 23.74 0 0 0-10.34 2.35L144 68.69V48h64zM168 96a8 8 0 1 1-8 8a8 8 0 0 1 8-8");
}

.cuyn6tgcc {
  fill: currentColor;
}

.d-lzeh97n {
  d: path("M208 40H48a8 8 0 0 0-8 8v160a8 8 0 0 0 8 8h160a8 8 0 0 0 8-8V48a8 8 0 0 0-8-8M88 184a16 16 0 1 1 16-16a16 16 0 0 1-16 16m80-64a16 16 0 1 1 16-16a16 16 0 0 1-16 16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
