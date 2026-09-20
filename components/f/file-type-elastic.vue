<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="moci_0bpl"/><path class="b62q1irzj"/><path class="gc_go8bid"/><path class="kse28ubhk"/><path class="itrj32p3x"/><path class="k4f0brbao"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:file-type-elastic" /></template>
<style>
.b62q1irzj {
  fill: var(--svg-color--24bbb1, #24bbb1);
  d: path("M5.886 20.919a7.3 7.3 0 0 0-.141 1.5a7.514 7.514 0 0 0 13.724 4.22l1.1-5.759l-1.469-2.821l-6.67-3.04Z");
}

.gc_go8bid {
  fill: var(--svg-color--ef5098, #ef5098);
  d: path("M5.848 9.426L10.4 10.5l1-5.169a3.594 3.594 0 0 0-5.552 4.095");
}

.itrj32p3x {
  fill: var(--svg-color--93c83e, #93c83e);
  d: path("M20.624 26.639a3.589 3.589 0 0 0 5.541-4.092l-4.541-1.065Z");
}

.k4f0brbao {
  fill: var(--svg-color--0779a1, #0779a1);
  d: path("m21.547 20.29l5 1.167A5.016 5.016 0 0 0 26.768 12l-6.541 5.733Z");
}

.kse28ubhk {
  fill: var(--svg-color--17a8e0, #17a8e0);
  d: path("M5.45 10.517a5.016 5.016 0 0 0-.218 9.453l6.388-5.77l-1.167-2.5Z");
}

.moci_0bpl {
  fill: var(--svg-color--fed10a, #fed10a);
  d: path("m12.761 13.89l6.644 3.027l6.7-5.874a7 7 0 0 0 .141-1.475a7.484 7.484 0 0 0-13.66-4.233l-1.12 5.785Z");
}

</style>
