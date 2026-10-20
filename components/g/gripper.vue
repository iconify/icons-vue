<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u26z0vbys"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:gripper" /></template>
<style>
.u26z0vbys {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 2L12 7M14.4575 11.7207L19.5841 15.4104C20.0353 15.7351 20.1351 16.3655 19.8061 16.8137L16 22M9.5425 11.7207L4.4159 15.4104C3.9647 15.7351 3.8649 16.3655 4.1939 16.8137L8 22M15 10C15 11.6569 13.6569 13 12 13C10.3431 13 9 11.6569 9 10C9 8.3431 10.3431 7 12 7C13.6569 7 15 8.3431 15 10Z");
}

</style>
