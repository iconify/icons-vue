<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oyfr40bxc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:file-chart-column" /></template>
<style>
.oyfr40bxc {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M14 2L8 2C5.7909 2 4 3.7909 4 6L4 18C4 20.2091 5.7909 22 8 22L16 22C18.2091 22 20 20.2091 20 18L20 8L14 2ZM14 2L14 5C14 6.6569 15.3431 8 17 8L20 8M8 18L8 14M12 18L12 15M16 18L16 12");
}

</style>
