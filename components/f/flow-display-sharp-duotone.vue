<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kk7_knm0f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:flow-display-sharp-duotone" /></template>
<style>
.kk7_knm0f {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M15 5C18.866 5 22 8.134 22 12C22 15.866 18.866 19 15 19L8 19L2.0023 12L8 5Z");
}

</style>
