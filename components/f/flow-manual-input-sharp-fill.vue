<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="um26q3msw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:flow-manual-input-sharp-fill" /></template>
<style>
.um26q3msw {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M11.8039 6.0196L21.8039 4.0198C21.8685 4.0069 21.9342 4.0004 22 4.0004C22.5523 4.0004 23 4.4481 23 5.0004L23 19C23 19.5523 22.5523 20 22 20L2 20C1.4477 20 1 19.5523 1 19L1 8.9999C1 8.5232 1.3365 8.1128 1.8039 8.0193Z");
}

</style>
