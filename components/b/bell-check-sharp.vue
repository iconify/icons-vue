<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u3p8yx2tq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:bell-check-sharp" /></template>
<style>
.u3p8yx2tq {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M15.254 11.0546C16.1706 13.7121 17 14.356 17 15L17 16L3 16L3 15C3 14 5 13 5 8C5 5.2386 7.2386 3 10 3C10.7111 3 11.3875 3.1484 12.9164 3.8164M7.7679 19.134C8.6252 20.6188 9.2855 21 10 21C10.7145 21 11.3748 20.6188 12.2321 19.134M15.7071 4.7071L18 7L22.2929 2.7071");
}

</style>
