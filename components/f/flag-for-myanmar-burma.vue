<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="yk1c3qbrz"/><path class="qj9-mya5r"/><path class="d8kxhub2n"/><path class="xfi-0baut"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:flag-for-myanmar-burma" /></template>
<style>
.d8kxhub2n {
  fill: var(--svg-color--fecb01, #fecb01);
  d: path("M32 5H4a4 4 0 0 0-4 4v4h36V9a4 4 0 0 0-4-4");
}

.qj9-mya5r {
  fill: var(--svg-color--34b232, #34b232);
  d: path("M0 13h36v10H0z");
}

.xfi-0baut {
  fill: var(--svg-color--fff, #fff);
  d: path("M18 8.76L20.353 16h7.613l-6.159 4.333l2.352 7.169L18 22.992l-6.159 4.458l2.353-7.107L8.035 16h7.613z");
}

.yk1c3qbrz {
  fill: var(--svg-color--ea2839, #ea2839);
  d: path("M0 27a4 4 0 0 0 4 4h28a4 4 0 0 0 4-4v-4H0z");
}

</style>
