<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="x_p78f8lx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:anime-witcher" /></template>
<style>
.x_p78f8lx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m39.187 13.079l-7.03 21.842l-7.031-21.842l-7.031 21.842l-7.031-21.842M4.5 20.221l39 11.871");
}

</style>
