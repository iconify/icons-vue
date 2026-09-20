<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="l7rnjqcxf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:filmstrip-globe-32-regular" /></template>
<style>
.l7rnjqcxf {
  fill: currentColor;
  d: path("M25.973 24c-.196 3.67-1.453 6.5-2.974 6.5s-2.778-2.83-2.974-6.5zm-7.45 0c.09 1.833.428 3.525.962 4.86c.139.346.296.682.474.998A7.51 7.51 0 0 1 15.565 24zm11.91 0a7.51 7.51 0 0 1-4.393 5.858c.178-.316.335-.652.474-.998c.534-1.334.87-3.027.96-4.86zM25.5 4A4.5 4.5 0 0 1 30 8.5v8.845a9 9 0 0 0-2-1.83V8.5A2.5 2.5 0 0 0 25.5 6h-19A2.5 2.5 0 0 0 4 8.5v15A2.5 2.5 0 0 0 6.5 26h8.014a9 9 0 0 0 1.003 2H6.5A4.5 4.5 0 0 1 2 23.5v-15A4.5 4.5 0 0 1 6.5 4zM7 20a1 1 0 0 1 1 1v2a1 1 0 1 1-2 0v-2a1 1 0 0 1 1-1m12.959-3.858a8 8 0 0 0-.474.998c-.582 1.455-.93 3.336-.98 5.36h-2.99a7.5 7.5 0 0 1 4.444-6.358m3.04-.642c1.59 0 2.89 3.091 2.993 7h-5.986c.103-3.909 1.404-7 2.993-7m3.041.642a7.5 7.5 0 0 1 4.442 6.358h-2.989c-.05-2.024-.397-3.905-.98-5.36a8 8 0 0 0-.473-.998M7 14a1 1 0 0 1 1 1v2a1 1 0 1 1-2 0v-2a1 1 0 0 1 1-1m0-6a1 1 0 0 1 1 1v2a1 1 0 1 1-2 0V9a1 1 0 0 1 1-1m18 0a1 1 0 0 1 1 1v2a1 1 0 1 1-2 0V9a1 1 0 0 1 1-1");
}

</style>
