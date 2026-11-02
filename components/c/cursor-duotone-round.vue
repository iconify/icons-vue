<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="rlitoibdi"/><path class="rm-z7ybxs"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:cursor-duotone-round" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.rlitoibdi {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M18.316 7.051c.392.131.754.338 1.066.609c.584.506 1.041 1.28.917 2.077c-.078.503-.398.93-.852 1.157l-2 1c-.154.077-.185.266-.185.422c0 .367.19.722.445.977l2 2a2.414 2.414 0 0 1 0 3.414l-1 1a2.414 2.414 0 0 1-3.414 0l-2-2c-.255-.255-.61-.445-.977-.445c-.156 0-.345.031-.422.185l-1 2a1.56 1.56 0 0 1-1.157.852c-.797.124-1.571-.333-2.077-.917a3.2 3.2 0 0 1-.609-1.066l-4-12a2.582 2.582 0 0 1 3.265-3.265Z");
}

.rm-z7ybxs {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("m12 6l6 2c1.107.369 1.738 1.631 1 2l-2 1c-.984.492-.984 2.016 0 3l2 2a1.414 1.414 0 0 1 0 2l-1 1a1.414 1.414 0 0 1-2 0l-2-2c-.984-.984-2.508-.984-3 0l-1 2c-.369.738-1.631.107-2-1L4 6c-.412-1.236.764-2.412 2-2z");
}

</style>
