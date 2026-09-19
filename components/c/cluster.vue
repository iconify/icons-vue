<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="wzep2mb4x"/><path class="fpobxw57u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:cluster" /></template>
<style>
.fpobxw57u {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M29.994 21.517a2.688 2.688 0 0 0 0 4.966l8.051 3.335l5.818-14.046l-8.228-3.408M18.006 26.483a2.688 2.688 0 0 0 0-4.966l-8.051-3.335l-5.818 14.046l8.228 3.408m9.152-17.63a2.688 2.688 0 0 0 4.966 0l3.335-8.051l-14.046-5.818l-3.408 8.228m14.119 17.629a2.688 2.688 0 0 0-4.966 0l-3.335 8.051l14.046 5.818l3.408-8.228");
}

.wzep2mb4x {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M29.994 26.483a2.687 2.687 0 0 0-3.511 3.511l3.335 8.052l14.046-5.818L40.456 24m-22.45-2.483a2.687 2.687 0 0 0 3.511-3.511l-3.335-8.052l-14.045 5.818L7.543 24m18.94-5.994a2.687 2.687 0 0 0 3.511 3.511l8.052-3.335l-5.818-14.045L24 7.543m-2.483 22.451a2.687 2.687 0 0 0-3.511-3.511l-8.052 3.335l5.818 14.046L24 40.456");
}

</style>
