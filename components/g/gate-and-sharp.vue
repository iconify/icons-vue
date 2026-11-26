<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yx47rvucp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:gate-and-sharp" /></template>
<style>
.yx47rvucp {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M7 5L11 5C14.866 5 18 8.134 18 12C18 15.866 14.866 19 11 19L7 19ZM1 8L7 8M1 16L7 16M18 12L23 12");
}

</style>
