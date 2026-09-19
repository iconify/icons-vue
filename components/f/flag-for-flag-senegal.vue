<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="mawct3gym"/><path class="wu8efm62y"/><path class="ys9oyvb-b"/><path class="pou5yswhm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione-v1:flag-for-flag-senegal" /></template>
<style>
.mawct3gym {
  fill: var(--svg-color--f9cb38, #f9cb38);
  d: path("M18 10h28v44H18z");
}

.pou5yswhm {
  fill: var(--svg-color--137a08, #137a08);
  d: path("m41.11 28.22l-6.679.01l-2.074-6.471L30.3 28.23l-6.695-.01l5.425 3.95l-2.098 6.433l5.442-4l5.437 4l-2.101-6.433z");
}

.wu8efm62y {
  fill: var(--svg-color--137a08, #137a08);
  d: path("M10 10C3.373 10 0 14.925 0 21v22c0 6.075 3.373 11 10 11h10V10z");
}

.ys9oyvb-b {
  fill: var(--svg-color--ec1c24, #ec1c24);
  d: path("M54 10H44v44h10c6.627 0 10-4.925 10-11V21c0-6.075-3.373-11-10-11");
}

</style>
