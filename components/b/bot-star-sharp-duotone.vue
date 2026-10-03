<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="s4wt0lbfe"/><path class="czv8fxbyr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:bot-star-sharp-duotone" /></template>
<style>
.czv8fxbyr {
  d: path("M10.8705 9.7535L11.5816 14.4178M14.8248 9.1507L15.5359 13.815");
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.s4wt0lbfe {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M13.2583 1.9378L16.1771 5.0217L20.3877 5.5704C21.882 5.7652 23 7.0383 23 8.5453C23 9.0466 22.8744 9.5399 22.6346 9.9802L20.6035 13.7092L21.3829 17.8832C21.4167 18.0648 21.4338 18.2491 21.4338 18.4338C21.4338 20.0907 20.0907 21.4338 18.4338 21.4338C18.2491 21.4338 18.0648 21.4167 17.8832 21.3829L13.7092 20.6035L9.9802 22.6346C9.5399 22.8744 9.0466 23 8.5453 23C7.0383 23 5.7652 21.882 5.5704 20.3877L5.0217 16.1771L1.9378 13.2583C1.3392 12.6917 1 11.9037 1 11.0794C1 9.9216 1.6663 8.8671 2.712 8.37L6.547 6.547L8.37 2.712C8.8671 1.6663 9.9216 1 11.0794 1C11.9037 1 12.6917 1.3392 13.2583 1.9378Z");
  stroke: none;
}

</style>
