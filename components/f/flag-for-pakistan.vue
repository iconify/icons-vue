<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="qq50accvm"/><path class="ds9o-cp5u"/><g class="y43ufvdry"><path class="kci8i0byx"/><path class="r10wb9a2q"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione-v1:flag-for-pakistan" /></template>
<style>
.ds9o-cp5u {
  fill: var(--svg-color--006838, #006838);
  d: path("M54 10H20v44h34c6.627 0 10-4.925 10-11V21c0-6.075-3.373-11-10-11");
}

.kci8i0byx {
  d: path("m44.509 21.528l2.264 2.101l3.01-.671l-1.298 2.806l1.57 2.66l-3.073-.374l-2.044 2.319l-.593-3.03l-2.84-1.231l2.7-1.506z");
}

.qq50accvm {
  fill: var(--svg-color--e6e7e8, #e6e7e8);
  d: path("M10 10C3.373 10 0 14.925 0 21v22c0 6.075 3.373 11 10 11h10V10z");
}

.r10wb9a2q {
  d: path("M52.37 35.33c-4.301 4.302-11.272 4.302-15.574 0s-4.302-11.273 0-15.574c.297-.296.607-.567.927-.822a12.64 12.64 0 0 0-5.829 3.312c-4.966 4.967-4.966 13.02 0 17.987c4.969 4.966 13.02 4.966 17.987 0a12.64 12.64 0 0 0 3.312-5.829a12 12 0 0 1-.823.926");
}

.y43ufvdry {
  fill: var(--svg-color--e6e7e8, #e6e7e8);
}

</style>
