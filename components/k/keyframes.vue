<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kp6uwabth"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:keyframes" /></template>
<style>
.kp6uwabth {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M8.6022 3.4453C8.7877 3.1671 9.0999 3 9.4343 3C9.7686 3 10.0808 3.1671 10.2663 3.4453L15.7845 11.7226C15.8393 11.8048 15.8685 11.9013 15.8685 12C15.8685 12.0987 15.8393 12.1952 15.7845 12.2774L10.2663 20.5547C10.0808 20.8329 9.7686 21 9.4343 21C9.0999 21 8.7877 20.8329 8.6022 20.5547L3.084 12.2774C3.0292 12.1952 3 12.0987 3 12C3 11.9013 3.0292 11.8048 3.084 11.7226L8.6022 3.4453ZM15.1009 3L20.916 11.7226C20.9708 11.8048 21 11.9013 21 12C21 12.0987 20.9708 12.1952 20.916 12.2774L15.1009 21");
}

</style>
