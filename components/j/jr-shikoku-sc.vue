<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="b2mm3m4kj"/><path class="xusaw2b1v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:jr-shikoku-sc" /></template>
<style>
.b2mm3m4kj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m4.91 24.995l10.046 9.953a1.519 1.505 0 0 0 2.074.068l5.898-5.113a1.624 1.609 0 0 1 2.138 0l5.899 5.113a1.519 1.505 0 0 0 2.073-.068l10.046-9.953a1.42 1.408 0 0 0 0-1.99l-10.046-9.953a1.519 1.505 0 0 0-2.073-.069l-5.899 5.114a1.624 1.609 0 0 1-2.138 0l-5.898-5.114a1.519 1.505 0 0 0-2.074.069L4.91 23.004a1.42 1.408 0 0 0 0 1.991");
}

.xusaw2b1v {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m9.263 29.308l6.697-5.972h9.376l10.716 8.626m-10.716-8.626v-3.207h14.845m-14.845 0l-2.409-2.033");
}

</style>
