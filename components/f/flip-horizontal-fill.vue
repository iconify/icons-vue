<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path clip-rule="evenodd" class="zhw3scb6d"/><path class="jobn-6uul"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:flip-horizontal-fill" /></template>
<style>
.jobn-6uul {
  d: path("M12 2L12 4M12 8L12 10M12 14L12 16M12 20L12 22");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.zhw3scb6d {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M0.9999 8C0.9995 6.8953 1.8949 5.9996 2.9996 5.9996C3.5302 5.9996 4.0391 6.2105 4.4142 6.5858L8.4142 10.5858C8.7892 10.9609 9 11.4696 9 12C9 12.5304 8.7892 13.0391 8.4142 13.4142L4.4142 17.4142C4.0391 17.7895 3.5302 18.0004 2.9996 18.0004C1.8949 18.0004 0.9995 17.1047 0.9999 16L0.9999 8ZM23.0001 8C23.0005 6.8953 22.1051 5.9996 21.0004 5.9996C20.4698 5.9996 19.9609 6.2105 19.5858 6.5858L15.5858 10.5858C15.2108 10.9609 15 11.4696 15 12C15 12.5304 15.2108 13.0391 15.5858 13.4142L19.5858 17.4142C19.9609 17.7895 20.4698 18.0004 21.0004 18.0004C22.1051 18.0004 23.0005 17.1047 23.0001 16L23.0001 8Z");
  stroke: none;
}

</style>
