<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="wezttabol"/><path class="gnm26lbqb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:campsite-available" /></template>
<style>
.gnm26lbqb {
  d: path("m9 17l1.5-4.5L12 17m-9.5 3H10m4.75-2l2 2L21 15.75");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.wezttabol {
  d: path("M12.121 17H5.516q-.057 0-.114-.004q-.057-.003-.114-.011q-.057-.007-.113-.018q-.056-.012-.111-.026q-.055-.015-.109-.033q-.055-.019-.107-.04q-.053-.022-.105-.048q-.051-.025-.1-.053q-.05-.029-.098-.06q-.047-.032-.093-.067q-.045-.035-.088-.072q-.043-.038-.084-.078q-.04-.041-.078-.083t-.073-.089q-.034-.045-.066-.092q-.032-.048-.061-.097q-.029-.05-.054-.101t-.047-.104t-.041-.107t-.033-.109t-.027-.111q-.011-.056-.019-.113q-.007-.057-.011-.114t-.004-.114t.003-.114t.011-.114t.018-.113t.025-.111t.033-.11t.04-.107t.047-.104t.053-.101l5.03-8.803q.028-.049.059-.097q.032-.047.066-.092q.034-.046.072-.089t.077-.083t.082-.078t.087-.073T9.561 5t.096-.061t.1-.054q.05-.026.103-.048t.106-.041t.108-.035q.055-.015.11-.027q.056-.011.112-.019t.113-.013q.057-.004.114-.005q.056-.001.113.002t.113.01t.113.016q.056.011.111.025q.055.013.109.031q.054.017.107.038t.104.045t.101.052t.098.058t.093.065t.089.07q.044.037.085.076q.041.04.079.082t.074.086t.068.091t.062.095l5.344 8.803q.222.365.25.792");
}

</style>
