<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<g class="cuyn6tgcc"><path class="vtjmi6vih"/><path class="ngxw9yb4h"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:google-play-logo-duotone" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.ngxw9yb4h {
  d: path("M239.82 114.18L72 18.16a16 16 0 0 0-16.12 0A15.68 15.68 0 0 0 48 31.87v192.26a15.68 15.68 0 0 0 7.92 13.67a16 16 0 0 0 16.12 0l167.78-96a15.76 15.76 0 0 0 0-27.64ZM64 212.67V43.33L148.69 128Zm96-73.36l18.92 18.92l-88.5 50.66ZM90.4 47.1l88.53 50.67L160 116.69ZM193.31 150l-22-22l22-22l38.43 22Z");
}

.vtjmi6vih {
  d: path("M160 128L58.32 230a7.7 7.7 0 0 1-2.32-5.55V31.55A7.7 7.7 0 0 1 58.32 26Z");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
