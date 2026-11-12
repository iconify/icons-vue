<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="tf5rnkipa"/><path class="x_757hbgu"/><path class="ujkefybfc"/><path class="my5268blj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:clipboard-text-linear" /></template>
<style>
.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.my5268blj {
  d: path("M9.5 6H14.5C15.3284 6 16 5.32843 16 4.5V3.5C16 2.67157 15.3284 2 14.5 2H9.5C8.67157 2 8 2.67157 8 3.5V4.5C8 5.32843 8.67157 6 9.5 6Z");
}

.tf5rnkipa {
  d: path("M16 4.00171C18.175 4.01382 19.3529 4.11027 20.1213 4.87865C21 5.75733 21 7.17154 21 9.99997V16C21 18.8284 21 20.2426 20.1213 21.1213C19.2426 22 17.8284 22 15 22H9C6.17157 22 4.75736 22 3.87868 21.1213C3 20.2426 3 18.8284 3 16V9.99997C3 7.17154 3 5.75733 3.87868 4.87865C4.64706 4.11027 5.82497 4.01382 8 4.00171");
}

.ujkefybfc {
  d: path("M7 18H12.5");
}

.x_757hbgu {
  d: path("M7 14.5H15");
}

</style>
