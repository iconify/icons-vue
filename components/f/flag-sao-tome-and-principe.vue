<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="m-2g36bzu"/><path class="jao6h-bvb"/><path class="q5gfugbib"/><path class="aqixrs0ox"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:flag-sao-tome-and-principe" /></template>
<style>
.aqixrs0ox {
  d: path("m18.004 20.36l1.625-1.181l1.624 1.181l-.62-1.91l1.624-1.181h-2.008l-.62-1.909l-.621 1.909H17l1.625 1.181zm9.5 0l1.625-1.181l1.624 1.181l-.62-1.91l1.624-1.181h-2.008l-.62-1.909l-.621 1.909H26.5l1.625 1.181z");
}

.jao6h-bvb {
  fill: var(--svg-color--ffce00, #ffce00);
  d: path("M8.173 13.5H36v9H8.173z");
}

.m-2g36bzu {
  fill: var(--svg-color--12ad2b, #12ad2b);
  d: path("M32 5H4a4 4 0 0 0-4 4v18a4 4 0 0 0 4 4h28a4 4 0 0 0 4-4V9a4 4 0 0 0-4-4");
}

.q5gfugbib {
  fill: var(--svg-color--d21034, #d21034);
  d: path("M1.149 6.195A3.98 3.98 0 0 0 0 9v18c0 1.093.438 2.083 1.148 2.805L12.5 18z");
}

</style>
