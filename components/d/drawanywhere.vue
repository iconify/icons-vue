<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="omgti7byw"/><path class="kxn5o2xey"/><path class="tb7ihh8ph"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:drawanywhere" /></template>
<style>
.kxn5o2xey {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M35.9 5.503c-1.24.041-2.576.491-3.867 1.637c-3.027 2.688-9.694 9.73-11.768 11.67c-2.508 2.347-3.502 5.17-4.432 7.678c-.852 2.293-1.766 4.54-.867 5.822q.149.21.339.383c.126.116.242.243.383.34c1.293.882 3.53-.016 5.823-.867c2.507-.931 5.33-1.924 7.677-4.432c1.94-2.075 8.982-8.742 11.67-11.768c3.058-3.445 1.158-7.215-.227-8.6c-.867-.867-2.664-1.932-4.73-1.863Z");
}

.omgti7byw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M40.846 21.609v12.146c0 4.845-3.9 8.745-8.745 8.745H14.246a8.726 8.726 0 0 1-8.745-8.745V15.9c0-4.845 3.9-8.745 8.745-8.745h12.006");
}

.tb7ihh8ph {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M30.379 8.684c1.03 4.886 4.47 7.638 8.843 9.033");
}

</style>
