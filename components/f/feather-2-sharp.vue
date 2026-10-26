<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t4g0w6bgq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:feather-2-sharp" /></template>
<style>
.t4g0w6bgq {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M4 22L4 21C4 19.8 4.2919 18.7366 4.5109 17.5453M4.5109 17.5453C5.5566 11.8125 8.4823 3.0471 19.1444 3L20 3.0838L19.9948 3.8963C19.3251 9.7234 9.5166 10.7285 14.5144 10.3551C20.8834 9.8792 12.8956 16.7176 4.5109 17.5453Z");
}

</style>
