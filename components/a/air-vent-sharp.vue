<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v1yupccki"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:air-vent-sharp" /></template>
<style>
.v1yupccki {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M18 13L22 13L22 3L2 3L2 13L6 13M5 9L19 9M14 12L14 19C14 20.1046 14.8954 21 16 21C17.1046 21 18 20.1046 18 19L18 17M9.5 12L9.5 17C9.5 18.1046 8.6046 19 7.5 19C6.3954 19 5.5 18.1046 5.5 17L5.5 16");
}

</style>
