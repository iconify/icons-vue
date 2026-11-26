<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ab6j2imud"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:flow-stored-data-duotone" /></template>
<style>
.ab6j2imud {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M9 5L21 5C21.5523 5 22 5.4477 22 6C22 6.3148 21.8518 6.6111 21.6 6.8C19.9633 8.0276 19 9.9541 19 12C19 14.0459 19.9633 15.9724 21.6 17.2C21.8518 17.3889 22 17.6852 22 18C22 18.5523 21.5523 19 21 19L9 19C5.134 19 2 15.866 2 12C2 8.134 5.134 5 9 5Z");
}

</style>
