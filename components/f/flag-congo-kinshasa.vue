<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="dagrjul6g"/><path class="uyt7k9bpa"/><path class="b0b5pyu_g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:flag-congo-kinshasa" /></template>
<style>
.b0b5pyu_g {
  fill: var(--svg-color--ce1021, #ce1021);
  d: path("M34.127 5.624L0 26.1v.9c0 1.425.751 2.668 1.873 3.376L36 9.9V9a3.99 3.99 0 0 0-1.873-3.376");
}

.dagrjul6g {
  fill: var(--svg-color--007fff, #007fff);
  d: path("M4 31h28a4 4 0 0 0 4-4V11.25L3.215 30.921c.254.05.516.079.785.079M32 5H4a4 4 0 0 0-4 4v15.75L32.785 5.079A4 4 0 0 0 32 5M9.63 16.02l-3.06-2.34l-3.06 2.34l1.17-3.78L1.62 9.9H5.4l1.17-3.78L7.74 9.9h3.78l-3.06 2.34z");
}

.uyt7k9bpa {
  fill: var(--svg-color--f7d618, #f7d618);
  d: path("M7.74 9.9L6.57 6.12L5.4 9.9H1.62l3.06 2.34l-1.17 3.78l3.06-2.34l3.06 2.34l-1.17-3.78l3.06-2.34zM3.215 30.921L36 11.25V9.9L1.873 30.376c.406.256.856.448 1.342.545m29.57-25.842L0 24.75v1.35L34.127 5.624a4 4 0 0 0-1.342-.545");
}

</style>
