<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oouyjsbqr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:fold-horizontal-sharp" /></template>
<style>
.oouyjsbqr {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M1 12L8 12M4.7071 8.7071L8 12L4.7071 15.2929M23 12L16 12M19.2929 8.7071L16 12L19.2929 15.2929M12 4L12 20");
}

</style>
