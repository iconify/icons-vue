<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ydwhgkuvu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:flash-off" /></template>
<style>
.ydwhgkuvu {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12.712 8.801L13.5 2.5l-3.166 3.87m-3.546 4.334L4.5 13.5h5.087m1.691 1.774L10.5 21.5l3.182-3.889m3.546-4.334L19.5 10.5h-5.012M3.5 3.5l17 17");
}

</style>
