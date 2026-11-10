<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="owlfxkbwe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:align-vertical-distribute-end" /></template>
<style>
.owlfxkbwe {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M22 20H2M22 10H2M16 16V18C16 19.105 15.1046 20 14 20H10C8.8954 20 8 19.105 8 18V16C8 14.895 8.8954 14 10 14H14C15.1046 14 16 14.895 16 16ZM18 10H6C4.8954 10 4 9.105 4 8V6C4 4.895 4.8954 4 6 4H18C19.1046 4 20 4.895 20 6V8C20 9.105 19.1046 10 18 10Z");
}

</style>
