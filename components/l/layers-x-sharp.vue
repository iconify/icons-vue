<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="niatp8byw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:layers-x-sharp" /></template>
<style>
.niatp8byw {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 2L22 7.5L12 13L2 7.5ZM1.4819 11.7151L12.2251 17.6238M1.4819 16.2151L12.2251 22.1238M15.7071 15.7071L22.2929 22.2929M22.2929 15.7071L15.7071 22.2929");
}

</style>
