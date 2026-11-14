<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oxk3bsbsu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:downvote" /></template>
<style>
.oxk3bsbsu {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M16.44 10.75h-.69V4.5q0-1.75-1.75-1.75h-4q-1.75 0-1.75 1.75v6.25h-.69q-1.645 0-2.296 1.511t.479 2.706l4.44 4.701q.74.783 1.817.783t1.817-.783l4.44-4.701q1.13-1.195.479-2.706T16.44 10.75M9.75 4.5q0-.25.25-.25h4q.25 0 .25.25v6.25h-4.5z");
}

</style>
