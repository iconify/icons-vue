<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kj_nmyqbp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:chevrons-four-directions-fill" /></template>
<style>
.kj_nmyqbp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M5.2929 15.5L2.1464 12.35C1.9512 12.16 1.9512 11.84 2.1464 11.65L5.2929 8.5M8.5 18.71L11.6464 21.85C11.8417 22.05 12.1583 22.05 12.3536 21.85L15.5 18.71M15.5 5.29L12.3536 2.15C12.1583 1.95 11.8417 1.95 11.6464 2.15L8.5 5.29M18.7071 15.5L21.854 12.35C22.049 12.16 22.049 11.84 21.854 11.65L18.7071 8.5");
}

</style>
