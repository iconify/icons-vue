<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wjv9hlb2n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:grid-circles-plus-sharp" /></template>
<style>
.wjv9hlb2n {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M6.5 21C8.433 21 10 19.433 10 17.5C10 15.567 8.433 14 6.5 14C4.567 14 3 15.567 3 17.5C3 19.433 4.567 21 6.5 21ZM6.5 10C8.433 10 10 8.433 10 6.5C10 4.567 8.433 3 6.5 3C4.567 3 3 4.567 3 6.5C3 8.433 4.567 10 6.5 10ZM17.5 10C19.433 10 21 8.433 21 6.5C21 4.567 19.433 3 17.5 3C15.567 3 14 4.567 14 6.5C14 8.433 15.567 10 17.5 10ZM18 14L18 22M14 18L22 18");
}

</style>
