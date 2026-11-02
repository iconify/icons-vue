<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="m3_mppelh"/><path class="s-i3zxb3b"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:bear-duotone-round" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.m3_mppelh {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M3.822 8.993C3.052 7.457 3.542 5.719 4.9 4.7a3.7 3.7 0 0 1 1.131-.581c.42-.133.863-.183 1.302-.147a3.33 3.33 0 0 1 1.911.823c1.818-.723 3.694-.723 5.512 0a3.33 3.33 0 0 1 1.911-.823c.868-.072 1.74.208 2.433.728c1.358 1.019 1.848 2.757 1.078 4.293c.78 1.31 1.304 2.769 1.443 4.291c.127 1.395-.079 2.834-.695 4.099C19.602 21.219 15.592 21.999 12 22c-3.592-.001-7.602-.781-8.926-4.617c-.616-1.265-.822-2.704-.695-4.099c.139-1.522.663-2.981 1.443-4.291");
}

.s-i3zxb3b {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M5 9C3 6.333 7 3.333 9 6q3-1.5 6 0c2-2.667 6 .333 4 3c2 3 2 6 1 8c-1 3-4 4-8 4s-7-1-8-4c-1-2-1-5 1-8m4 3h.01M15 12h.01M11 16h2l-1 1Z");
}

</style>
