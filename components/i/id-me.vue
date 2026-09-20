<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="fvjcaolsi"/><path class="v9h3bi3zv"/><path class="bbj6xitks"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:id-me" /></template>
<style>
.bbj6xitks {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m40.022 21.501l-5.648 5.388l-2.442-2.443");
}

.fvjcaolsi {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M32.227 33.133c.02.08.02.159.02.239v3.77H4.5v-3.77c0-1.264.776-2.408 1.96-2.875l7.919-3.134c1.045-.408 1.323-1.791.478-2.547c-1.552-1.393-2.567-3.681-2.567-6.268c0-4.248 2.726-7.69 6.088-7.69c3.353 0 6.079 3.442 6.079 7.69c0 2.587-1.015 4.875-2.567 6.268c-.845.756-.567 2.139.478 2.547l6.476 2.557v.01");
}

.v9h3bi3zv {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M34.92 14.436c-1.569 1.323-3.036 2.157-6.947 2.92a.78.78 0 0 0-.636.764v7.038c0 4.463 4.11 8.871 8.081 8.871c3.841 0 8.082-4.408 8.082-8.871V18.12a.78.78 0 0 0-.637-.763c-3.91-.764-5.377-1.598-6.945-2.921a.78.78 0 0 0-.999 0Z");
}

</style>
