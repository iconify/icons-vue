<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g3-0zi3ig"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:dish-brush" /></template>
<style>
.g3-0zi3ig {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m12.53 5.813l5.657 5.657a2 2 0 0 1 0 2.828a2 2 0 0 1-2.828 0L9.702 8.641a2 2 0 0 1 0-2.828a2 2 0 0 1 2.828 0m0 5.657za1.5 1.5 0 0 1 0 2.121l-5.48 5.48a1.5 1.5 0 0 1-2.121 0a1.5 1.5 0 0 1 0-2.121l5.48-5.48a1.5 1.5 0 0 1 2.121 0m1.768-8.132l-2.121 2.121m4.242 0l-2.121 2.122m4.243 0l-2.122 2.121m4.243 0l-2.121 2.121");
}

</style>
