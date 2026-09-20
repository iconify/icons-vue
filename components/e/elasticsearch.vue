<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":288};
const content = `<path class="l-iphjtxn"/><path class="lvvisrbsr"/><path class="h29ryxmby"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="logos:elasticsearch" /></template>
<style>
.h29ryxmby {
  fill: var(--svg-color--00bfb3, #00bfb3);
  d: path("M211.334 206.742H14.774c23.336 47.839 72.226 80.9 129.045 80.9c45.393 0 85.816-21.088 112.18-53.933a136.6 136.6 0 0 0-13.987-14.94c-8.36-7.721-19.299-12.027-30.678-12.027");
}

.l-iphjtxn {
  fill: var(--svg-color--343741, #343741);
  d: path("M0 143.82c0 12.44 1.744 24.441 4.71 35.956h175.067c19.856 0 35.955-16.1 35.955-35.956c0-19.865-16.1-35.955-35.955-35.955H4.71C1.744 119.371 0 131.38 0 143.82");
}

.lvvisrbsr {
  fill: var(--svg-color--fec514, #fec514);
  d: path("M242.013 68.863c5.025-4.629 9.7-9.6 13.987-14.93C229.636 21.079 189.213 0 143.82 0C87 0 38.101 33.052 14.775 80.9h196.559c11.38 0 22.319-4.324 30.678-12.037");
}

</style>
