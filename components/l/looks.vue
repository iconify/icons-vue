<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kiu8gtb8p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:looks" /></template>
<style>
.kiu8gtb8p {
  fill: currentColor;
  d: path("M1 17q0-2.275.863-4.275t2.362-3.5t3.5-2.363T12 6t4.275.863t3.5 2.362t2.363 3.5T23 17h-2q0-3.725-2.637-6.363T12 8t-6.362 2.638T3 17zm4 0q0-2.9 2.05-4.95T12 10t4.95 2.05T19 17h-2q0-2.075-1.463-3.537T12 12t-3.537 1.463T7 17z");
}

</style>
