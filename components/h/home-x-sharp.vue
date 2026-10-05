<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t-hxdm1ut"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:home-x-sharp" /></template>
<style>
.t-hxdm1ut {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12.3859 5.0748L11 3.9963L2 11L2 22L20 22L20 11M8 22L8 15L14 15L14 22M15.7071 1.7071L16 2L22 8L22.2929 8.2929M22.2929 1.7071L22 2L16 8L15.7071 8.2929");
}

</style>
