<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gga2dabrz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:list-sort-sharp-fill" /></template>
<style>
.gga2dabrz {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M6 11L6 3M2.7071 6.2929L6 3L9.2929 6.2929M6 13L6 21M2.7071 17.7071L6 21L9.2929 17.7071M12 6L22 6M12 12L22 12M12 18L22 18");
}

</style>
