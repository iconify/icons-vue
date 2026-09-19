<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="whc52obvb"/><path class="h5527s6rw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione-monotone:flag-for-djibouti" /></template>
<style>
.h5527s6rw {
  fill: currentColor;
  d: path("M32 2C15.432 2 2 15.432 2 32s13.432 30 30 30s30-13.432 30-30S48.568 2 32 2m0 31L12.934 52.48C7.443 47.365 4 40.078 4 32s3.443-15.365 8.934-20.48L32 31h28a56 56 0 0 1 0 2z");
}

.whc52obvb {
  fill: currentColor;
  d: path("M15.935 30.279L14.3 25.117l-1.588 5.162H7.417l4.235 3.352l-1.604 5.252l4.252-3.229l4.251 3.229l-1.603-5.252l4.236-3.352z");
}

</style>
