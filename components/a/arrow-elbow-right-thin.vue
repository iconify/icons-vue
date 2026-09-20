<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="ocd47pb9a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:arrow-elbow-right-thin" /></template>
<style>
.ocd47pb9a {
  fill: currentColor;
  d: path("M236 80v72a4 4 0 0 1-8 0V89.66L122.83 194.83a4 4 0 0 1-5.66 0l-96-96a4 4 0 0 1 5.66-5.66L120 186.34L222.34 84H160a4 4 0 0 1 0-8h72a4 4 0 0 1 4 4");
}

</style>
