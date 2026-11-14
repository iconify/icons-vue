<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="etnchxvpy"/><path class="j7fa-kb0t"/><path class="qjjhlxbaj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:database-heart" /></template>
<style>
.etnchxvpy {
  d: path("M14.137 21.149c-.681.066-1.398.101-2.137.101c-4.4 0-8-1.25-8-2.75v-13C4 4 7.6 2.75 12 2.75S20 4 20 5.5v6.955");
}

.j7fa-kb0t {
  d: path("M4 5.5C4 7 7.6 8.25 12 8.25S20 7 20 5.5M4 12c0 1.5 3.6 2.75 8 2.75q.363 0 .718-.011m7.154-2.253A1 1 0 0 0 20 12");
}

.qjjhlxbaj {
  d: path("M4 5.5C4 7 7.6 8.25 12 8.25S20 7 20 5.5M4 12c0 1.2 2.3 2.2 5.5 2.5m8.5 6.25s-3-2-3-3.75c0-1 .75-1.75 1.5-1.75s1.25.5 1.5 1c.25-.5.75-1 1.5-1S21 16 21 17c0 1.75-3 3.75-3 3.75Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
