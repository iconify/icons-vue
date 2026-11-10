<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="be6dqzoqj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:guidepoint-vertical-arrow-left" /></template>
<style>
.be6dqzoqj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M17 8C18.6568 8 20 6.66 20 5C20 3.34 18.6568 2 17 2C15.3432 2 14 3.34 14 5C14 6.66 15.3432 8 17 8ZM17 8V16M17 16C15.3432 16 14 17.34 14 19C14 20.66 15.3432 22 17 22C18.6568 22 20 20.66 20 19C20 17.34 18.6568 16 17 16ZM9.251 8.07L4.2523 11.52C3.9159 11.73 3.9159 12.27 4.2523 12.48L9.251 15.93C9.5847 16.14 10 15.87 10 15.45V8.55C10 8.13 9.5847 7.86 9.251 8.07Z");
}

</style>
