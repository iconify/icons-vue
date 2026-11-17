<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tf9lrtbjs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:cloud-moon-rain-fill" /></template>
<style>
.tf9lrtbjs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M8.5 18.598C7.572 18.062 7 17.072 7 16C7 14.343 8.343 13 10 13C10 10.515 12.015 8.5 14.5 8.5C16.985 8.5 19 10.515 19 13C20.657 13 22 14.343 22 16C22 17.072 21.428 18.062 20.5 18.598M3.719 12.904C2.614 11.704 2 10.132 2 8.5C2 4.91 4.91 2 8.5 2C7.844 2.82 7.487 3.839 7.487 4.889C7.487 5.747 7.725 6.588 8.176 7.318M12.5 19V22M16.5 19V22");
}

</style>
