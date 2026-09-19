<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="c-ha4o17g"/><path class="sdpw4bcrw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:libremchat" /></template>
<style>
.c-ha4o17g {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M17.08 27.3h9.75a9.22 9.22 0 0 0 0-18.44H13.51a9.22 9.22 0 0 0-1.38 18.33v4.38Zm9.2-10.58a1.6 1.6 0 0 1 0 3.19a1.2 1.2 0 0 1-.27 0a1.6 1.6 0 0 1 .27-3.19m-7.49 1.58a1.6 1.6 0 1 1 1.59 1.61a1.6 1.6 0 0 1-1.59-1.61m-4.3-1.58a1.6 1.6 0 0 1 0 3.19a1 1 0 0 1-.26 0a1.6 1.6 0 0 1 .26-3.19");
}

.sdpw4bcrw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M13.79 30.17a8.77 8.77 0 0 0 7.56 4.38h9.86l4.39 3.73v-3.84a8.76 8.76 0 0 0 7.49-6.59c1.17-4.7-2.14-10-7-10.63");
}

</style>
