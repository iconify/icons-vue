<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="umawzj_9e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:babbel-english" /></template>
<style>
.umawzj_9e {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M36.43 24.001a4.82 4.82 0 0 1 4.863 5.905a7.35 7.35 0 0 1-6.946 5.905h-9.743l4.165-23.62h9.742a4.82 4.82 0 0 1 4.864 5.906A7.35 7.35 0 0 1 36.43 24m0 0h-9.743m-6.49 0H4.5m8.654-4.564l.578-3.284m-2.767 15.696L12.348 24m9.095-7.039v-4.772l3.161 4.772v-4.772m-7.674 2.386h1.555m.831 2.386H16.93v-4.772h2.386");
}

</style>
