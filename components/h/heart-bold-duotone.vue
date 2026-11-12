<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ayqtpboig"/><path class="vhfpguceu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:heart-bold-duotone" /></template>
<style>
.ayqtpboig {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M8.10627 18.2468C5.29819 16.0833 2 13.5422 2 9.1371C2 4.27416 7.50016 0.825464 12 5.50063V20.5C11 20.5 10 19.7294 8.96173 18.9109C8.68471 18.6925 8.39814 18.4717 8.10627 18.2468Z");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.vhfpguceu {
  fill: currentColor;
  d: path("M15.0383 18.9109C17.9806 16.5914 22 14 22 9.1371C22 4.27416 16.4998 0.825464 12 5.50063V20.5C13 20.5 14 19.7294 15.0383 18.9109Z");
}

</style>
