<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="t1ywl-bwc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:bluetooth-slash-light" /></template>
<style>
.t1ywl-bwc {
  fill: currentColor;
  d: path("m220.44 212l-160-176a6 6 0 0 0-8.88 8l72.32 79.55L60.4 171.2a6 6 0 0 0 7.2 9.6L122 140v84a6 6 0 0 0 9.6 4.8l52.28-39.21L211.56 220a6 6 0 0 0 8.88-8.08ZM134 212v-72l15.09 11.31l26.68 29.36ZM122 71.63V32a6 6 0 0 1 9.6-4.8l64 48a6 6 0 0 1 0 9.6L162.07 110a6 6 0 0 1-7.2-9.6L182 80l-48-36v27.63a6 6 0 0 1-12 0");
}

</style>
