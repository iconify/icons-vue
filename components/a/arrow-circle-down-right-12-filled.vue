<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="gw-ju3bgc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:arrow-circle-down-right-12-filled" /></template>
<style>
.gw-ju3bgc {
  fill: currentColor;
  d: path("M6 1a5 5 0 1 1 0 10A5 5 0 0 1 6 1m1.5 3a.5.5 0 0 0-.5.5v1.793L4.854 4.146l-.079-.064a.5.5 0 0 0-.693.693l.064.079L6.293 7H4.5a.5.5 0 0 0 0 1h3a.5.5 0 0 0 .5-.5v-3a.5.5 0 0 0-.5-.5");
}

</style>
