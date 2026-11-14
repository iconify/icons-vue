<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="b7iczsbvb"/><path class="k0-q5k9wu"/><path class="ob6at5bfl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:database-clock" /></template>
<style>
.b7iczsbvb {
  d: path("M4 5.5C4 4 7.6 2.75 12 2.75S20 4 20 5.5v13c0 1.5-3.6 2.75-8 2.75S4 20 4 18.5Z");
}

.k0-q5k9wu {
  d: path("M4 5.5C4 7 7.6 8.25 12 8.25S20 7 20 5.5M8.5 14.75a3.5 3.5 0 1 0 7 0a3.5 3.5 0 1 0-7 0Z");
}

.ob6at5bfl {
  d: path("M12 13v1.75l1.25 1");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
