<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ehlps7bkk"/><path class="tll8q3h0v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:brain-waves" /></template>
<style>
.ehlps7bkk {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M23.935 24c3.887-5.69 8.516-9.49 12.93-8.972c2.772.325 6.635 2.588 6.635 8.972s-3.863 8.647-6.635 8.972c-4.414.517-9.043-3.283-12.93-8.972");
}

.tll8q3h0v {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24.065 24c-3.887-5.69-8.516-9.49-12.93-8.972C8.363 15.353 4.5 17.616 4.5 24s3.863 8.647 6.635 8.972c4.414.517 9.043-3.283 12.93-8.972");
}

</style>
