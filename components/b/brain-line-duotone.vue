<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="hf_-_gbgn"/><path class="e4iu9bc8j"/><path class="slsuh_zzt"/><path class="f56d9ccde"/><path class="ysu0dnbfq"/><path class="zyme4hbkr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:brain-line-duotone" /></template>
<style>
.e4iu9bc8j {
  d: path("M9.3465 10.1999C7.98322 10.7054 6.5361 10.0275 6.11426 8.68582");
}

.f56d9ccde {
  d: path("M11.7511 18.7411C11.7511 19.1376 11.9025 22.0307 15.5031 21.9999C20.0038 21.9615 23.3792 16.1829 20.928 12.1379C21.6782 10.7124 22.3507 7.46082 19.0396 5.85823C19.0781 3.65305 16.7848 2.04124 14.7523 2.00097C13.3194 1.97257 11.7511 3.20919 11.7511 4.60213V18.7411Z");
}

.hf_-_gbgn {
  d: path("M11.7509 18.7411C11.7509 19.1376 11.5995 22.0307 7.99889 21.9999C3.49813 21.9615 0.122706 16.1829 2.5739 12.1379C1.82374 10.7124 1.1512 7.46082 4.46233 5.85823C4.42387 3.65305 6.71718 2.04124 8.74963 2.00097C10.1826 1.97257 11.7509 3.20919 11.7509 4.60213V18.7411Z");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.slsuh_zzt {
  d: path("M8.45587 17.2585C7.0926 17.764 5.64547 17.0861 5.22363 15.7444");
}

.ysu0dnbfq {
  d: path("M14.1553 10.1999C15.5186 10.7054 16.9657 10.0275 17.3875 8.68582");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.zyme4hbkr {
  d: path("M15.0459 17.2585C16.4092 17.764 17.8563 17.0861 18.2781 15.7444");
  opacity: var(--svg-opacity--0-5, 0.5);
}

</style>
