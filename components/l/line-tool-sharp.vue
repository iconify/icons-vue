<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="vh3teb6kr"/><circle class="jb8wwbf-o"/><path class="zsroyjbnd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:line-tool-sharp" /></template>
<style>
.jb8wwbf-o {
  cx: 12px;
  cy: 10px;
  r: 1.25px;
}

.vh3teb6kr {
  d: path("M12 2.75L17.15 8l.691.781l-.491.919L15 14.25H9L6.65 9.7l-.491-.919L6.85 8Zm0 2v4");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.zsroyjbnd {
  d: path("M10 17.25h4v4h-4zm-6.25 2H7.5m9 0h3.75");
}

</style>
