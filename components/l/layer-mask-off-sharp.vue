<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j__7fd4eu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:layer-mask-off-sharp" /></template>
<style>
.j__7fd4eu {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M4 4L2 4L2 20L20 20M8.657 4L22 4L22 17.343M14.8284 14.8284C14.0783 15.5786 13.0609 16 12 16C9.7909 16 8 14.2091 8 12C8 10.9391 8.4214 9.9217 9.1716 9.1716M1.7071 1.7071L22.2929 22.2929");
}

</style>
