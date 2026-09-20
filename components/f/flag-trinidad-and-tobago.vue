<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="zg2e86bqr"/><path class="kmekqkbcu"/><path class="rspn5mxfg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:flag-trinidad-and-tobago" /></template>
<style>
.kmekqkbcu {
  fill: var(--svg-color--eee, #eee);
  d: path("M2.23 5.412a4 4 0 0 0-1.081.783L24.99 31h1.835zM11.01 5H9.175l24.594 25.588c.404-.2.77-.465 1.082-.783z");
}

.rspn5mxfg {
  fill: var(--svg-color--141414, #141414);
  d: path("M4 5c-.635 0-1.236.148-1.769.412L26.825 31H32c.635 0 1.235-.148 1.768-.411l.002-.001L9.175 5z");
}

.zg2e86bqr {
  fill: var(--svg-color--ce1126, #ce1126);
  d: path("M1.148 6.196A4 4 0 0 0 0 9v18a4 4 0 0 0 4 4h20.99L1.149 6.195zM32 5H11.01l23.841 24.805A3.98 3.98 0 0 0 36 27V9a4 4 0 0 0-4-4");
}

</style>
