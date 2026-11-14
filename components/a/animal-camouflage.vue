<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wow0q1f3f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:animal-camouflage" /></template>
<style>
.wow0q1f3f {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M17.125 1.75H6.875q-2.123 0-3.624 1.501T1.75 6.875v10.25q0 2.123 1.501 3.624t3.624 1.501h10.25q2.123 0 3.624-1.501t1.501-3.624V6.875q0-2.123-1.501-3.624T17.125 1.75M4.75 8q0-2.159 1.566-3.268q1.363-.965 3.277-.726q1.899.237 2.519 1.959l.019.054q1.883-.888 3.856-.231q2.033.678 2.668 2.776q.613 2.022-.519 3.833q-.587.94-1.539 1.431q1.904 1.207 1.647 3.265q-.458 3.209-6.562 2.654Q5.75 19.253 5.75 16.5q0-2.119 2.275-3.32q1.18-.622 2.509-.753q-.311-.491-.498-1.053q-.291.141-.619.246q-1.725.555-3.028-.212Q4.75 10.568 4.75 8");
}

</style>
