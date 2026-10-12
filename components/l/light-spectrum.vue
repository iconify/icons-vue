<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t3jfr0b6y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:light-spectrum" /></template>
<style>
.t3jfr0b6y {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 10.5c.08-.13.33-.52.5-.8c.17-.27.33-.55.5-.83s.33-.57.5-.84c.17-.28.33-.55.5-.81c.17-.25.33-.5.5-.71c.17-.22.33-.42.5-.57s.33-.28.5-.35s.33-.11.5-.08s.33.1.5.24s.33.34.5.6s.33.58.5.95s.33.81.5 1.27s.33.98.5 1.5c.17.51.33 1.08.5 1.6s.33 1.06.5 1.53s.33.93.5 1.27c.17.35.33.65.5.82s.33.25.5.19c.17-.05.33-.22.5-.51s.33-.72.5-1.22s.33-1.14.5-1.78c.17-.65.33-1.4.5-2.09s.33-1.43.5-2.03s.33-1.19.5-1.58c.17-.38.33-.67.5-.74c.17-.08.33.02.5.31c.17.28.33.78.5 1.37c.17.6.33 1.41.5 2.2s.33 1.73.5 2.52s.33 1.63.5 2.2c.17.58.33 1.06.5 1.25c.17.18.33.14.5-.14c.17-.29.33-.88.5-1.57c.17-.7.33-1.7.5-2.6c.17-.91.33-2.01.5-2.84c.17-.82.33-1.66.5-2.11s.42-.49.5-.59M2.75 19.5h18.5");
}

</style>
