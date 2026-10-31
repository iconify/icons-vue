<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="huakagbvk"/><path class="xofc3l91p"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:bottle-pump-fill" /></template>
<style>
.huakagbvk {
  fill: currentColor;
  d: path("M16 10.1263C17.7661 10.5827 18.9999 12.1759 19 14L19 19C19 21.2092 17.2092 23 15 23L9 23C6.7908 23 5 21.2092 5 19L5 14C5.0001 12.1759 6.2339 10.5827 8 10.1263L8 7.5C8 6.6716 8.6716 6 9.5 6L14.5 6C15.3284 6 16 6.6716 16 7.5L16 10.1263Z");
  stroke: none;
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.xofc3l91p {
  d: path("M12 2L12 7M9 2L13.1716 2C14.9826 2 16.7194 2.7194 18 4");
}

</style>
