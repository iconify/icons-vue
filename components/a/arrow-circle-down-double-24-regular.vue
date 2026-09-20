<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i12nq_73f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:arrow-circle-down-double-24-regular" /></template>
<style>
.i12nq_73f {
  fill: currentColor;
  d: path("m11.25 13.75l-.085-.073a.75.75 0 0 0-.976.073l-.69.69V7.75l-.007-.102A.75.75 0 0 0 8.75 7l-.102.006A.75.75 0 0 0 8 7.75v6.691l-.69-.69l-.084-.074a.75.75 0 0 0-.976 1.133l1.969 1.971l.084.073a.75.75 0 0 0 .977-.073l1.97-1.97l.073-.085a.75.75 0 0 0-.072-.976M1.999 12c0 5.523 4.477 10 10 10s10-4.477 10-10s-4.477-10-10-10s-10 4.477-10 10m18.5 0a8.5 8.5 0 1 1-17 0a8.5 8.5 0 0 1 17 0m-2.75 1.75l-.084-.073a.75.75 0 0 0-.976.073l-.69.69V7.75l-.007-.102a.75.75 0 0 0-.743-.649l-.102.007a.75.75 0 0 0-.648.743v6.692l-.69-.69l-.083-.074a.75.75 0 0 0-.977 1.133l1.969 1.971l.084.073a.75.75 0 0 0 .977-.073l1.97-1.97l.073-.085a.75.75 0 0 0-.072-.976");
}

</style>
