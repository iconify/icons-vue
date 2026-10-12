<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jwpebzbhr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:kayak" /></template>
<style>
.jwpebzbhr {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 14.5c4.25-3.25 14.25-3.25 18.5 0C17 17.75 7 17.75 2.75 14.5m7.25 0h4m-6.5 6l9-16m.21-.45l.38-.85q.21-.45.69-.31l1.24.37q.48.14.27.59l-1.48 3.1q-.21.45-.39-.02l-.74-1.96q-.18-.47.03-.92M7.14 20.84l-.08.07q-.36.34-.84.2l-1.24-.37q-.48-.14-.27-.59l1.48-3.1q.21-.45.35.03l.82 2.94q.14.48-.22.82");
}

</style>
