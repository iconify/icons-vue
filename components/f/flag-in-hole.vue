<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="g324xhbnn"/><path class="c0aootbdf"/><path class="y-7-0_b_b"/><path class="ax13difaq"/><path class="ty49jc2xb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noto:flag-in-hole" /></template>
<style>
.ax13difaq {
  fill: var(--svg-color--f7c875, #f7c875);
  d: path("M66.59 3.75c-1.71 0-2.44 1.08-2.44 2.35v81s.71 1.05 2.61 1.05c1.89 0 2.62-1.05 2.62-1.05l-.36-81.72s-.35-1.63-2.43-1.63");
}

.c0aootbdf {
  fill: var(--svg-color--b7d118, #b7d118);
  d: path("M20.84 75.45c.78 4.23 10.22 4.94 16.48 13.02s8.9 14.87 18.29 18.62c6.59 2.64 19.15 5.8 38.89-.33c21.75-6.76 17.44-28.13-16.48-35.26c-32.13-6.76-58.33-2.31-57.18 3.95");
}

.g324xhbnn {
  fill: var(--svg-color--94a61d, #94a61d);
  d: path("M5.35 78.58c.29 8.9 14.31 9.69 21.42 15c9.72 7.25 13.51 21.75 24.72 26.04s27.03 6.43 45.15 2.31s28.43-14.81 25.38-25.71c-3.79-13.51-20.76-26.7-54.38-30.32s-51.08 1.98-54.87 3.46s-7.58 4.12-7.42 9.22");
}

.ty49jc2xb {
  fill: var(--svg-color--ff4f28, #ff4f28);
  d: path("M117.29 16.92c.26.44-3.01 4.02-7.77 6.68c-6.13 3.43-16.96 8.21-22.37 10.28s-10.32 3.77-13.08 5.32c-2.06 1.16-4.51 4.69-5.05 4.24c-.28-.24-.32-10.59-.43-20.36c-.1-8.93.17-17.08.34-17.25c.36-.36 1.17-.63 1.9 0s6.8 3.39 15.28 5.91s15.68 4.21 21.72 4.48s9.19.25 9.46.7");
}

.y-7-0_b_b {
  fill: var(--svg-color--4a4a29, #4a4a29);
  d: path("M67.57 81.62c-6.13-.27-10.37 1.6-10.37 6.04c0 3.79 4.6 5.41 10.37 5.41c6.95 0 8.84-2.98 8.75-5.59c-.1-2.97-2.24-5.57-8.75-5.86");
}

</style>
