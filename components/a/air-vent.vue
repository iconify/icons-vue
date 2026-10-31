<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ad308pb-r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:air-vent" /></template>
<style>
.ad308pb-r {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M19 13C20.6569 13 22 11.6569 22 10L22 6C22 4.3431 20.6569 3 19 3L5 3C3.3431 3 2 4.3431 2 6L2 10C2 11.6569 3.3431 13 5 13M6 9L18 9M14 13L14 19C14 20.1046 14.8954 21 16 21C17.1046 21 18 20.1046 18 19L18 18M9.5 13L9.5 17C9.5 18.1046 8.6046 19 7.5 19C6.3954 19 5.5 18.1046 5.5 17");
}

</style>
