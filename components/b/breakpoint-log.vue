<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="luzbd0b8t"/><path class="ei--gqbuz"/><path class="e6r6vi0vd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:breakpoint-log" /></template>
<style>
.e6r6vi0vd {
  d: path("M12.5 10.25h6");
}

.ei--gqbuz {
  fill: currentColor;
  d: path("M5.5 10.25a2 2 0 1 0 4 0a2 2 0 1 0-4 0Z");
}

.luzbd0b8t {
  d: path("M5 3.5h14A2.5 2.5 0 0 1 21.5 6v8.5A2.5 2.5 0 0 1 19 17h-9l-4 3.5V17H5a2.5 2.5 0 0 1-2.5-2.5V6A2.5 2.5 0 0 1 5 3.5Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
