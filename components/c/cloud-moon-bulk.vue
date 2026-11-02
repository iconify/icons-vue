<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="pd583sppo"/><path class="mpubfw_8a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:cloud-moon-bulk" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.mpubfw_8a {
  d: path("M20.375 8.22c.166-.132.369-.209.581-.218h.009A.997.997 0 0 1 22 9v.001a6.97 6.97 0 0 1-1.231 3.964a6.97 6.97 0 0 1-3.26 2.57a1 1 0 0 1-1.275-.534V15a1 1 0 0 1 .558-1.333a5 5 0 0 0 2.888-2.906a5.27 5.27 0 0 1-6.441-6.443A5 5 0 0 0 10 9a1 1 0 0 1-2 0a7 7 0 0 1 7-7a1 1 0 0 1 .781 1.625a3.2 3.2 0 0 0-.518.919a3.265 3.265 0 0 0 1.736 4.107a3.27 3.27 0 0 0 3.376-.431");
}

.pd583sppo {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M5.667 22a3.668 3.668 0 0 1-.7-7.267a4.7 4.7 0 0 1 1.913-2.071a4.84 4.84 0 0 1 3.102-.568c2.138.322 3.657 1.935 3.959 4.057A3 3 0 0 1 13 22Z");
}

</style>
