<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="hen1-20qd"/><path class="k23o--9wi"/><path class="nathzfxes"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione:flag-for-triangular-flag" /></template>
<style>
.hen1-20qd {
  fill: var(--svg-color--ccc, #ccc);
  d: path("M26.2 61.5c0 1.4-4.3 2.5-9.7 2.5s-9.7-1.1-9.7-2.5s4.3-2.5 9.7-2.5c5.3 0 9.7 1.2 9.7 2.5");
}

.k23o--9wi {
  fill: var(--svg-color--ed4c5c, #ed4c5c);
  d: path("M56.1 17.7C54.2 16.8 23 2.1 18.4 0v39.5c4.5-2.1 35.7-16.8 37.6-17.7c1.6-.7 1.6-3.4.1-4.1");
}

.nathzfxes {
  fill: var(--svg-color--d3976e, #d3976e);
  d: path("M14.5 0h3.9v61.5h-3.9z");
}

</style>
