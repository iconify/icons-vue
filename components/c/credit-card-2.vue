<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y4mdc4bzu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:credit-card-2" /></template>
<style>
.y4mdc4bzu {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M2 15H22M14 9.5H17M2 7C2 5.3431 3.3431 4 5 4H19C20.6569 4 22 5.3431 22 7V17C22 18.6569 20.6569 20 19 20H5C3.3431 20 2 18.6569 2 17V7Z");
}

</style>
