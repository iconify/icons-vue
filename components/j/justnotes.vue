<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="g1fxjzwcx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:justnotes" /></template>
<style>
.g1fxjzwcx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m13.247 40.589l-7.71-.038l-.037-7.71L30.318 8.025a2.09 2.09 0 0 1 2.957 0l4.79 4.79c.816.816.816 2.14 0 2.957zm12.06-27.555l7.747 7.747m-8.232.486L10.086 36.002M42.5 32.466H30.506l-8.417 8.085H42.5z");
}

</style>
