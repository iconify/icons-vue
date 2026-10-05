<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="r2thrxbpb"/><path clip-rule="evenodd" class="g6hnddcux"/><path class="blkkxbc2n"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:file-cog-sharp-duotone" /></template>
<style>
.blkkxbc2n {
  d: path("M18.6667 18C18.6667 19.4728 17.4728 20.6667 16 20.6667C14.5272 20.6667 13.3333 19.4728 13.3333 18C13.3333 16.5272 14.5272 15.3333 16 15.3333C17.4728 15.3333 18.6667 16.5272 18.6667 18ZM18.99 18L21 18M18.1142 20.1142L19.5355 21.5355M16 20.99L16 23M13.8858 20.1142L12.4645 21.5355M13.01 18L11 18M13.8858 15.8858L12.4645 14.4645M16 15.01L16 13M18.1142 15.8858L19.5355 14.4645");
}

.g6hnddcux {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M13 1L14.4142 1L21 7.5858L21 9L13 9ZM15 4.4142L15 7L17.5858 7Z");
  stroke: none;
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.r2thrxbpb {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M14 1C14.2652 1 14.5195 1.10547 14.707 1.29297L20.707 7.29297C20.8945 7.48047 21 7.7348 21 8V10C21 10.5523 20.5523 11 20 11H9V22C9 22.5523 8.5523 23 8 23H4C3.4477 23 3 22.5523 3 22V2C3 1.4477 3.4477 1 4 1H14Z");
  stroke: none;
}

</style>
