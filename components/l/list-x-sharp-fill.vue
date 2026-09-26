<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xfmbv0bgy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:list-x-sharp-fill" /></template>
<style>
.xfmbv0bgy {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M1 4L23 4M1 11L23 11M1 18L7 18M9 18L15 18M17.7071 15.7071L22.2929 20.2929M22.2929 15.7071L17.7071 20.2929");
}

</style>
