<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="njxf9mbnc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:cloud-rain-fill" /></template>
<style>
.njxf9mbnc {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M8 17L8 21M12 17L12 21M16 17L16 21M4 16.4641C2.7624 15.7496 2 14.4291 2 13C2 10.7909 3.7909 9 6 9C6 5.6863 8.6863 3 12 3C15.3137 3 18 5.6863 18 9C20.2091 9 22 10.7909 22 13C22 14.4291 21.2376 15.7496 20 16.4641");
}

</style>
