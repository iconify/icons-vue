<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="z26_6acsz"/><path class="beytf36nq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:flame-alt-duotone-sharp" /></template>
<style>
.beytf36nq {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M10.5 21C2 14 8 8 12 3c4 5 10 11 1.5 18Zm0 0C6 17.5 8 14.5 12 11c4 3.5 6 6.5 1.5 10");
}

.ft5dv1b6b {
  fill: none;
}

.z26_6acsz {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M9.368 19.992C3.087 13.917 7.417 8.617 11.115 4.091Q11.56 3.548 12 3q.44.548.885 1.091c3.698 4.526 8.028 9.826 1.747 15.901c2.552-2.659 1.347-5.031-.886-7.348A27 27 0 0 0 12 11a27 27 0 0 0-1.746 1.644c-2.233 2.317-3.438 4.689-.886 7.348");
}

</style>
