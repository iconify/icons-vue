<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ei2igf-th"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:arrow-badge-left-bulk" /></template>
<style>
.ei2igf-th {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M19 20h-8a1 1 0 0 1-.707-.293l-6-6a2.414 2.414 0 0 1 0-3.414l6-6A1 1 0 0 1 11 4h8c.203-.001.402.047.582.14c.712.371.835 1.242.549 1.932a2 2 0 0 1-.424.635l-5 5a.414.414 0 0 0 0 .586l5 5c.182.182.326.398.424.635c.286.69.163 1.561-.549 1.932c-.18.093-.379.141-.582.14");
}

</style>
