<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="uzgr9cc-e"/><path class="t5k789jkh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:lantern-fanoos-sharp" /></template>
<style>
.t5k789jkh {
  d: path("M10.6 11H14l.21.56l.58 1.63l.21.56l-.31.51l-.88 1.48l-.31.51h-3l-.31-.51l-.88-1.48l-.31-.51l.21-.56l.58-1.63L10 11zm-1.1 7.5h5V21h-5z");
}

.uzgr9cc-e {
  d: path("M12 2.75v2m.35.35l3.05 3.05l.35.35h-7.5l.35-.35l3.05-3.05l.35-.35zm-4.1 3.4h8.25l.22.72l1.06 3.56l.22.72l-.34.67l-1.82 3.66l-.34.67h-7l-.34-.67l-1.82-3.66L6 13.5l.22-.72l1.06-3.56l.22-.72z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
