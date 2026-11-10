<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jyt_1sb6y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:ghost-sharp" /></template>
<style>
.jyt_1sb6y {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M14.5 23V21.78C14.5 20.25 15.745 19 17.281 19C18.335 19 19.298 19.6 19.769 20.54L20 21V10C20 5.58 16.418 2 12 2C7.582 2 4 5.58 4 10V21L4.231 20.54C4.702 19.6 5.665 19 6.719 19C8.255 19 9.5 20.25 9.5 21.78V23M9 8V11M15 8V11M14.5 23V21.5C14.5 20.12 13.381 19 12 19C10.619 19 9.5 20.12 9.5 21.5V23");
}

</style>
