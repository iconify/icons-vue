<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="ptn0u52ch"/><path class="y3qf9gidi"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:award-sharp-duotone" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.ptn0u52ch {
  stroke-opacity: 0.4;
  d: path("M16.1787 14.6152L19 21.9993L12 19.207L5 21.9993L7.8213 14.6152");
}

.y3qf9gidi {
  fill: currentColor;
  d: path("M12 1C16.4183 1 20 4.58172 20 9C20 13.4183 16.4183 17 12 17C7.58172 17 4 13.4183 4 9C4 4.58172 7.58172 1 12 1Z");
  stroke: none;
}

</style>
