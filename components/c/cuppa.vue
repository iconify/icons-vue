<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="t4wjxx5mh"/><path class="ozsveibdg"/><path class="hcrdl-bdz"/><ellipse class="tztwlx06p"/><path class="x2jyyqb_l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:cuppa" /></template>
<style>
.hcrdl-bdz {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M9.182 12.99c0 6.115 4.08 18.064 14.568 18.064s14.567-11.949 14.567-18.063");
}

.ozsveibdg {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M4.5 29.786c0 4.31 4.682 9.885 19.25 9.885S43 33.886 43 29.576");
}

.t4wjxx5mh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M11.999 23.395C7.438 24.822 4.5 27.06 4.5 29.576c0 4.31 8.618 7.804 19.25 7.804S43 33.886 43 29.576c0-2.516-2.938-4.754-7.498-6.181");
}

.tztwlx06p {
  cx: 23.75px;
  cy: 12.991px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 14.567px;
  ry: 4.662px;
}

.x2jyyqb_l {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M37.652 14.386c-1.704-1.944-7.283-3.369-13.902-3.369s-12.198 1.425-13.903 3.37m26.3 7.739c6.04 1.08 7.353-2.357 7.353-4.943s-.992-4.192-3.276-4.192a2.48 2.48 0 0 0-1.938.944");
}

</style>
