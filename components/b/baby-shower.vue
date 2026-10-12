<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="cuxd2-w0g"/><path class="hcl2dkb9n"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:baby-shower" /></template>
<style>
.cuxd2-w0g {
  d: path("M8.8 3h.4q.8 0 1.37.57l.86.86q.57.57 1.14 0l.86-.86Q14 3 14.8 3h.4q.8 0 1.44.47l3.47 2.56q.64.47.24 1.16l-1.2 2.12q-.4.69-1.13.37l-.79-.36q-.73-.32-.73.48v6.4q0 .8-.41 1.49l-1.68 2.87q-.41.69-1.21.69h-2.4q-.8 0-1.21-.69l-1.68-2.87Q7.5 17 7.5 16.2V9.8q0-.8-.73-.48l-.79.36q-.73.32-1.13-.37l-1.2-2.12q-.4-.69.24-1.16l3.47-2.56Q8 3 8.8 3");
}

.hcl2dkb9n {
  d: path("m12 14.48l-1.54-1.54c-.33-.32-.66-.7-.66-1.21c0-.67.54-1.21 1.21-1.21c.39 0 .66.11.99.44c.33-.33.6-.44.99-.44c.67 0 1.21.54 1.21 1.21c0 .51-.33.89-.66 1.21Z");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
