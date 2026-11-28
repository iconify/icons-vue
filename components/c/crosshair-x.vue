<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bp3m2wb8f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:crosshair-x" /></template>
<style>
.bp3m2wb8f {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M20 12C20 16.4183 16.4183 20 12 20C7.5817 20 4 16.4183 4 12C4 7.5817 7.5817 4 12 4C16.4183 4 20 7.5817 20 12ZM12 2V6M12 22V18M2 12H6M22 12H18M9.5 9.5L14.5 14.5M14.5 9.5L9.5 14.5");
}

</style>
