<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yo0aq_b_a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:anonymous" /></template>
<style>
.yo0aq_b_a {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9.979 13.633Q10.956 14 12 14q1.042 0 2.018-.366m1.397-10.01q-.369-.272-.775-.482q-.407-.211-.842-.354q-.436-.143-.888-.215T12 2.5t-.908.072t-.884.214q-.434.143-.84.352t-.774.479M4 21.5c0-3 3.5-4.75 8-4.75s8 1.75 8 4.75M4.5 8C4.5 6.5 7 6 9 6.5l3 1l3-1c2-.5 4.5 0 4.5 1.5c0 2.5-2.5 3.5-4.5 3l-3-1.25L9 11c-2 .5-4.5-.5-4.5-3");
}

</style>
