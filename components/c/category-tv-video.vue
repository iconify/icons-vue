<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="su8ihyb2e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:category-tv-video" /></template>
<style>
.su8ihyb2e {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M18.5 2.75h-13q-1.76 0-3.005 1.245T1.25 7v7q0 1.76 1.245 3.005T5.5 18.25h.459l-.671 2.013q-.023.07-.032.143t-.004.147t.025.145t.052.137t.079.125q.045.058.101.107q.055.048.12.085q.064.036.134.06q.141.047.29.036q.149-.01.282-.077q.134-.067.232-.18q.097-.112.145-.254l.829-2.487h8.918l.829 2.487q.024.07.06.134q.037.065.085.12q.049.056.107.101q.059.046.125.079t.137.052q.071.02.145.025t.147-.004t.143-.032q.07-.024.134-.06q.065-.037.12-.085q.056-.049.101-.107q.046-.059.079-.125t.052-.137q.02-.071.025-.145t-.004-.147t-.032-.143l-.671-2.013h.459q1.76 0 3.005-1.245T22.75 14V7q0-1.76-1.245-3.005T18.5 2.75M8.25 9.253q0-1.437 1.242-2.16t2.491-.015l2.199 1.246q1.269.718 1.269 2.176t-1.268 2.176l-2.2 1.245q-1.25.709-2.491-.014t-1.242-2.16z");
}

</style>
