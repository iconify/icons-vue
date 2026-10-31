<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a0x7vfb1f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:bottle-pump" /></template>
<style>
.a0x7vfb1f {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M9 11L15 11C16.6569 11 18 12.3431 18 14L18 19C18 20.6569 16.6569 22 15 22L9 22C7.3431 22 6 20.6569 6 19L6 14C6 12.3431 7.3431 11 9 11ZM9 11L9 7.5C9 7.2239 9.2239 7 9.5 7L14.5 7C14.7761 7 15 7.2239 15 7.5L15 11M12 2L12 7M9 2L13.1716 2C14.9826 2 16.7194 2.7194 18 4");
}

</style>
