<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x9njutb2m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:hanami-dango-sharp" /></template>
<style>
.x9njutb2m {
  fill: currentColor;
  d: path("m21.075 22.5l-2.125-2.125q-1.225.75-2.675.6T13.75 19.75q-.725-.725-1.025-1.662T12.55 16.2q-.95.125-1.888-.175T9 15t-1.025-1.662T7.8 11.45q-.95.125-1.888-.175T4.25 10.25Q3.175 9.175 3.025 7.713t.6-2.688L1.5 2.9l1.4-1.4l2.15 2.125q1.225-.75 2.675-.6T10.25 4.25q.725.725 1.025 1.65t.175 1.875q.95-.125 1.888.188T15 9t1.025 1.65t.175 1.875q.95-.125 1.888.188t1.662 1.037q1.075 1.075 1.225 2.525t-.6 2.675l2.125 2.125z");
}

</style>
