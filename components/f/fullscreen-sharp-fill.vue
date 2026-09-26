<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ph9zg-b4h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:fullscreen-sharp-fill" /></template>
<style>
.ph9zg-b4h {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M13 3L21 3L21 11M13.7071 10.2929L20.8243 3.1757M11 21L3 21L3 13M10.2929 13.7071L3.1757 20.8243");
}

</style>
