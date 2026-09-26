<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q_eafzcnl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:bookmark-plus" /></template>
<style>
.q_eafzcnl {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M20 12L20 20.9983C20 21.7895 19.1248 22.2673 18.4592 21.8395L12.8111 18.8514C12.317 18.5338 11.683 18.5338 11.1889 18.8514L5.5408 21.8395C4.8752 22.2673 4 21.7895 4 20.9983L4 5C4 3.3431 5.3431 2 7 2L10 2M17 2V8M14 5H20");
}

</style>
