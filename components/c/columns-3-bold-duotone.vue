<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j2-x-cbeh"/><path class="qykqcq_5w"/><path class="gyjvu3nrz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:columns-3-bold-duotone" /></template>
<style>
.gyjvu3nrz {
  fill: currentColor;
  d: path("M9.41602 20.999C8.87568 20.9985 8.37707 20.9937 7.91602 20.9863V3.0127C8.37706 3.00531 8.87569 3.0005 9.41602 3V20.999Z");
}

.j2-x-cbeh {
  fill: currentColor;
  d: path("M2 11C2 7.22876 2 5.34315 3.17157 4.17157C4.34315 3 6.22876 3 10 3H14C17.7712 3 19.6569 3 20.8284 4.17157C22 5.34315 22 7.22876 22 11V13C22 16.7712 22 18.6569 20.8284 19.8284C19.6569 21 17.7712 21 14 21H10C6.22876 21 4.34315 21 3.17157 19.8284C2 18.6569 2 16.7712 2 13V11Z");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.qykqcq_5w {
  fill: currentColor;
  d: path("M16.083 3.0127V20.9863C15.622 20.9937 15.1233 20.9995 14.583 21V3C15.1233 3.0005 15.622 3.00532 16.083 3.0127Z");
}

</style>
