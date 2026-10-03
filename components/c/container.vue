<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k0qq-hbap"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:container" /></template>
<style>
.k0qq-hbap {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M2 11C2 9.8954 2.8954 9 4 9L16 9C17.1046 9 18 9.8954 18 11L18 17C18 18.1046 17.1046 19 16 19L4 19C2.8954 19 2 18.1046 2 17L2 11ZM2.5858 9.5858L6.5858 5.5858C6.9609 5.2107 7.4696 5 8 5L20 5C21.1046 5 22 5.8954 22 7L22 13C22 13.5304 21.7893 14.0391 21.4142 14.4142L17.4142 18.4142M17.4142 9.5858L21.4142 5.5858M6 9L6 19M10 9L10 19M14 9L14 19");
}

</style>
