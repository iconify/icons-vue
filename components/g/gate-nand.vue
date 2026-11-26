<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m3n1cobng"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:gate-nand" /></template>
<style>
.m3n1cobng {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M9 5L11 5C14.866 5 18 8.134 18 12C18 15.866 14.866 19 11 19L9 19C7.8954 19 7 18.1046 7 17L7 7C7 5.8954 7.8954 5 9 5ZM2 8L7 8M2 16L7 16M18 12C18 10.8954 18.8954 10 20 10C21.1046 10 22 10.8954 22 12C22 13.1046 21.1046 14 20 14C18.8954 14 18 13.1046 18 12Z");
}

</style>
