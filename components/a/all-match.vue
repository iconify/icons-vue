<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ppoo3acul"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:all-match" /></template>
<style>
.ppoo3acul {
  fill: currentColor;
  d: path("m2 20l6-8l-6-8h13q.475 0 .9.213t.7.587L22 12l-.125.175Q21 11.6 20.025 11.3T18 11q-2.925 0-4.962 2.038T11 17.975q0 .5.075 1.013T11.3 20zm12.463 1.538Q13 20.075 13 18t1.463-3.537T18 13t3.538 1.463T23 18t-1.463 3.538T18 23t-3.537-1.463m2.812-1.287l3.475-3.45l-1.05-1.05l-2.425 2.375l-.975-.975l-1.05 1.075z");
}

</style>
