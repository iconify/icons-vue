<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jlcjwhb2d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:copy-off-sharp" /></template>
<style>
.jlcjwhb2d {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M2 2L2 16.0001L5 16M16 5L16.0001 2L6.6569 2M22 22L8 22L8 8M12.6569 8L22 8L22 17.3431M1.7071 1.7071L22.2929 22.2929");
}

</style>
