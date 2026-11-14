<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pjn7djbov"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:fighter-jet" /></template>
<style>
.pjn7djbov {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m12.75 5.5l.649 2.597a1.5 1.5 0 0 0 .395.697l6.267 6.267a1.5 1.5 0 0 1 .439 1.06v.129a.643.643 0 0 1-.741.636l-3.922-.603a1.108 1.108 0 0 0-1.212 1.467l.538 1.505a1.5 1.5 0 0 1 .087.505v.49a.554.554 0 0 1-.717.529l-2.092-.643a1.5 1.5 0 0 0-.882 0l-2.092.643a.554.554 0 0 1-.717-.529v-.49a1.5 1.5 0 0 1 .087-.505l.538-1.505a1.108 1.108 0 0 0-1.212-1.467l-3.922.603a.643.643 0 0 1-.741-.636v-.129a1.5 1.5 0 0 1 .439-1.06l6.267-6.267a1.5 1.5 0 0 0 .395-.697L11.25 5.5a.773.773 0 0 1 1.5 0M12 7v3.5");
}

</style>
