<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="jui0bmbic"/><path class="el8lonb1e"/><ellipse class="xzotmebie"/><path class="xzq1-sbiq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noto-v1:automobile" /></template>
<style>
.el8lonb1e {
  fill: var(--svg-color--2f2f2f, #2f2f2f);
  d: path("M39.79 109.43c0 6.38-5.17 11.55-11.55 11.55s-11.56-5.17-11.56-11.55s5.17-11.54 11.56-11.54c6.38 0 11.55 5.16 11.55 11.54");
}

.jui0bmbic {
  fill: var(--svg-color--006ca2, #006ca2);
  d: path("M104 58.98c3.26 4.44 5.69 9.29 8.18 11.78s5.46 5.61 10.24 10.39s7.52 15.86 2.75 23.52c-2.76 4.45-7.22 7.1-12.5 7.1H15.42c-3.5 0-6.84-.59-11.67-5.43c-5.23-5.23-3.79-17.83.18-22.24c5.17-5.77 16.71-7.31 20.48-11.08c3.76-3.76 5.52-10.11 9.08-15.3c5.88-8.57 13.97-11.5 22.48-11.5H78.7c12.26 0 20.16 5.78 25.3 12.76");
}

.xzotmebie {
  cx: 98.01px;
  cy: 109.44px;
  fill: var(--svg-color--2f2f2f, #2f2f2f);
  rx: 11.55px;
  ry: 11.54px;
}

.xzq1-sbiq {
  fill: var(--svg-color--40c0e7, #40c0e7);
  d: path("M60.92 74.1c0 2.92-1.88 3.89-4.17 3.89h-16.3c-5.64 0-2.6-8.52 2.91-14.56s13.98-6.52 15.15-6.23c2.25.56 2.41 2.64 2.41 4.92zm5.48 0c0 2.92 2.71 3.89 6.03 3.89H96c8.15 0 3.42-11.87-4.87-17.46c-5.89-3.97-19.56-3.62-21.24-3.33c-3.25.56-3.49 2.64-3.49 4.92z");
}

</style>
