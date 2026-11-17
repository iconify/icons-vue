<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eqaw61tjf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:arrow-badge-left-bulk-round" /></template>
<style>
.eqaw61tjf {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M18 20h-6c-1.039 0-1.992-.578-2.707-1.293l-5-5a2.414 2.414 0 0 1 0-3.414l5-5C10.008 4.578 10.961 4 12 4h6c.898 0 1.928.572 2.089 1.521a1.34 1.34 0 0 1-.382 1.186l-5 5a.414.414 0 0 0 0 .586l5 5c.311.31.456.752.382 1.186C19.928 19.428 18.898 20 18 20");
}

</style>
