<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pg7u55lgh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:folders" /></template>
<style>
.pg7u55lgh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M4 9.268C3.3812 9.6253 3 10.2855 3 11V19C3 20.1046 3.8954 21 5 21H14C14.7145 21 15.3747 20.6188 15.732 20M8 5C8 3.8954 8.8954 3 10 3L11.1716 3C11.702 3 12.2107 3.2107 12.5858 3.5858L13.4142 4.4142C13.7893 4.7893 14.298 5 14.8284 5L19 5C20.1046 5 21 5.8954 21 7L21 14C21 15.1046 20.1046 16 19 16L10 16C8.8954 16 8 15.1046 8 14Z");
}

</style>
