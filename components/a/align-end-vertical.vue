<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="koxnu2bez"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:align-end-vertical" /></template>
<style>
.koxnu2bez {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M22 2V22M18 6V8C18 9.105 17.1046 10 16 10H12C10.8954 10 10 9.105 10 8V6C10 4.895 10.8954 4 12 4H16C17.1046 4 18 4.895 18 6ZM18 16V18C18 19.105 17.1046 20 16 20H4C2.8954 20 2 19.105 2 18V16C2 14.895 2.8954 14 4 14H16C17.1046 14 18 14.895 18 16Z");
}

</style>
