<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="a28xsovsv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:koober" /></template>
<style>
.a28xsovsv {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M26.006 8.33c3.773-3.773 9.89-3.773 13.664 0s3.773 9.89 0 13.664L21.994 39.67a9.66 9.66 0 0 1-13.664 0a9.66 9.66 0 0 1 0-13.664z");
}

</style>
