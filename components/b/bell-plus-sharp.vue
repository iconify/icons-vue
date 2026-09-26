<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="inf7f8bsf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:bell-plus-sharp" /></template>
<style>
.inf7f8bsf {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M15.254 11.0546C16.1706 13.7121 17 14.356 17 15L17 16L3 16L3 15C3 14 5 13 5 8C5 5.2386 7.2386 3 10 3C10.7111 3 11.3875 3.1484 12.9164 3.8164M7.7679 19.134C8.6252 20.6188 9.2855 21 10 21C10.7145 21 11.3748 20.6188 12.2321 19.134M19 1L19 9M15 5L23 5");
}

</style>
