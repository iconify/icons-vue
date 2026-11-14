<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wr-dc3b7f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:cabin-smoke" /></template>
<style>
.wr-dc3b7f {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9.5 11h5a2 2 0 0 1 2 2v6.5a2 2 0 0 1-2 2h-5a2 2 0 0 1-2-2V13a2 2 0 0 1 2-2ZM8 8Q6.5 6.5 8 5.25T8 2.5M12 8q-1.5-1.5 0-2.75t0-2.75M16 8q-1.5-1.5 0-2.75t0-2.75m-5.75 12h3.5");
}

</style>
