<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="g6_6jab3q"/><path class="jqo74lbth"/><path class="l1-0mcblx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione-v1:flag-for-flag-colombia" /></template>
<style>
.g6_6jab3q {
  fill: var(--svg-color--2b3990, #2b3990);
  d: path("M0 25h64v17H0z");
}

.jqo74lbth {
  fill: var(--svg-color--f9cb38, #f9cb38);
  d: path("M54 10H10C3.373 10 0 14.925 0 21v11h64V21c0-6.075-3.373-11-10-11");
}

.l1-0mcblx {
  fill: var(--svg-color--ec1c24, #ec1c24);
  d: path("M0 43c0 6.075 3.373 11 10 11h44c6.627 0 10-4.925 10-11v-1H0z");
}

</style>
