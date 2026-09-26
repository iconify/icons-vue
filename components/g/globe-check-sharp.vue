<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="riwnmkwkt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:globe-check-sharp" /></template>
<style>
.riwnmkwkt {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 22C6.4771 22 2 17.5228 2 12C2 6.4771 6.4771 2 12 2C17.5228 2 22 6.4771 22 12M2 12L22 12M12 2C14.6667 5 16 8.5 16 12M12 2C9.3333 5 8 8.5 8 12C8 15.5 9.3333 19 12 22M15.7055 19.2971L18.3333 22L22.1467 15.76");
}

</style>
