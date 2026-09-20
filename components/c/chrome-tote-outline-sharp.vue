<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cqpxpl-ly"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:chrome-tote-outline-sharp" /></template>
<style>
.cqpxpl-ly {
  fill: currentColor;
  d: path("M12.825 19h5.65v1.275L3.75 22.125L1.9 7.2l3.125-.35v2l-.9.1l1.35 10.95Zm-5.8-2V2h15v15Zm2-2h11V4h-11Zm-3.55 4.9Zm3.55-4.9V4v11Zm5.5-1.5l4-4l-1.4-1.425l-1.6 1.575V5.5h-2v4.15l-1.6-1.575l-1.4 1.425Z");
}

</style>
