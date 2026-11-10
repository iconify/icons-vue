<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gxbvu0bui"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:joystick" /></template>
<style>
.gxbvu0bui {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M14.7813 9.74C15.1537 9.91 15.5661 10 16 10C17.6569 10 19 8.66 19 7C19 5.34 17.6569 4 16 4C14.3431 4 13 5.34 13 7C13 8.22 13.7317 9.27 14.7813 9.74ZM14.7813 9.74L13.2184 13.26M5 14H19C20.1046 14 21 14.9 21 16V18C21 19.1 20.1046 20 19 20H5C3.8954 20 3 19.1 3 18V16C3 14.9 3.8954 14 5 14Z");
}

</style>
