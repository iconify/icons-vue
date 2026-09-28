<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="muxlvw8ru"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:circle-play-off" /></template>
<style>
.muxlvw8ru {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M19.0711 19.0711C17.2614 20.8807 14.7614 22 12 22C6.4772 22 2 17.5228 2 12C2 9.2386 3.1193 6.7386 4.9289 4.9289M8.3456 2.6888C9.4776 2.2442 10.7103 2 12 2C17.5228 2 22 6.4772 22 12C22 13.2897 21.7558 14.5224 21.3112 15.6544M8.9717 8.9717C8.9657 9.0161 8.9627 9.0608 8.9627 9.1055L8.9627 14.8945C8.9627 15.4467 9.4104 15.8945 9.9627 15.8945C10.1502 15.8945 10.3338 15.8418 10.4927 15.7425L13.7233 13.7233M2 2L22 22");
}

</style>
