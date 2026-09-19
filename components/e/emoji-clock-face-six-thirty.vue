<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="e1bqx3beu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:emoji-clock-face-six-thirty" /></template>
<style>
.e1bqx3beu {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24.043 39.899v-2.07M24.04 24v10.279M2.5 24c-.004 11.87 9.619 21.496 21.493 21.5S45.496 35.884 45.5 24.014V24c.004-11.87-9.619-21.496-21.493-21.5S2.504 12.116 2.5 23.986z");
}

</style>
