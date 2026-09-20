<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o04nh_-6m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:business-chip-outline-sharp" /></template>
<style>
.o04nh_-6m {
  fill: currentColor;
  d: path("M8 16h8v-6h-2V8h-4v2H8zm3-6V9h2v1zm-3 9q-2.925 0-4.962-2.037T1 12t2.038-4.962T8 5h8q2.925 0 4.963 2.038T23 12t-2.037 4.963T16 19zm0-2h8q2.075 0 3.538-1.463T21 12t-1.463-3.537T16 7H8Q5.925 7 4.463 8.463T3 12t1.463 3.538T8 17m4-5");
}

</style>
