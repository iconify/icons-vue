<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<circle class="cl66i7bqg"/><path class="n8rwppsqt"/><path class="wrft_xvmr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:magnifier-slash-bold-duotone" /></template>
<style>
.cl66i7bqg {
  cx: 11.5px;
  cy: 11.5px;
  r: 9.5px;
  fill: currentColor;
  opacity: var(--svg-opacity--0-5, 0.5);
}

.n8rwppsqt {
  fill: currentColor;
  d: path("M21.7889 20.766C22.0709 21.0482 22.0709 21.5062 21.7889 21.7884C21.5067 22.0705 21.0488 22.0705 20.7665 21.7884L17.6854 18.7074C18.0514 18.393 18.3925 18.0509 18.7069 17.6849L21.7889 20.766Z");
}

.wrft_xvmr {
  fill: currentColor;
  d: path("M12.7372 9.20152C13.0299 8.90888 13.5048 8.90909 13.7977 9.20152C14.0904 9.49442 14.0906 9.97021 13.7977 10.263L10.2626 13.7982C9.96975 14.0909 9.49489 14.0908 9.20202 13.7982C8.90918 13.5053 8.90927 13.0306 9.20202 12.7376L12.7372 9.20152Z");
}

</style>
