<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="rqxk3kbwo"/><path class="qflhlkbem"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:flag-for-somalia" /></template>
<style>
.qflhlkbem {
  fill: var(--svg-color--fff, #fff);
  d: path("M19.405 16.066L18 11.741l-1.405 4.325h-4.548l3.679 2.673l-1.405 4.325L18 20.391l3.679 2.673l-1.405-4.325l3.679-2.673z");
}

.rqxk3kbwo {
  fill: var(--svg-color--4189dd, #4189dd);
  d: path("M32 5H4a4 4 0 0 0-4 4v18a4 4 0 0 0 4 4h28a4 4 0 0 0 4-4V9a4 4 0 0 0-4-4");
}

</style>
