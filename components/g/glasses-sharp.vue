<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k68h7irsy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:glasses-sharp" /></template>
<style>
.k68h7irsy {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M10 15C10 17.2091 8.2091 19 6 19C3.7909 19 2 17.2091 2 15C2 12.7909 3.7909 11 6 11C8.2091 11 10 12.7909 10 15ZM22 15C22 17.2091 20.2091 19 18 19C15.7909 19 14 17.2091 14 15C14 12.7909 15.7909 11 18 11C20.2091 11 22 12.7909 22 15ZM10 15C11 13.5 13 13.5 14 15M2.489 13.0309L2.5 13L4.2924 7.9826C4.7424 6.8011 5.6202 5.8924 6.7041 5.486L8 5L8.1698 4.9363M21.511 13.0309L21.5 13L19.7076 7.9826C19.2576 6.8011 18.3798 5.8924 17.2959 5.486L16 5L15.8302 4.9363");
}

</style>
