<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d2aqg9dsz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:hearing-off-fill-sharp" /></template>
<style>
.d2aqg9dsz {
  fill: currentColor;
  d: path("m2.707 1.293l20 20a.999.999 0 1 1-1.414 1.414l-6.874-6.874C13.605 16.397 13 16.939 13 18a3.98 3.98 0 0 1-1.172 2.828A3.998 3.998 0 0 1 5 18V9a7 7 0 0 1 .361-2.225L1.293 2.707a.999.999 0 1 1 1.414-1.414M9.14 4.897l-1.43-1.43a7 7 0 0 1 7.371-.752A7 7 0 0 1 19 9c0 1.58-.399 3.106-1.416 4.342Z");
}

</style>
