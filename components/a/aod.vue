<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="saxd1zx5g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:aod" /></template>
<style>
.saxd1zx5g {
  fill: currentColor;
  d: path("M8.385 11.596h7.307v-1H8.385zm1 2.885h5.307v-1H9.385zM7.615 22q-.67 0-1.143-.472Q6 21.056 6 20.385V3.615q0-.69.463-1.152T7.616 2h8.846q.67 0 1.143.472q.472.472.472 1.144V6.83q.373.04.648.31q.275.269.275.648v1.769q0 .379-.275.648t-.648.31v9.869q0 .67-.472 1.143q-.472.472-1.143.472z");
}

</style>
