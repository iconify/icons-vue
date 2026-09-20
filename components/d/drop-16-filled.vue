<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="g61bstb3g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:drop-16-filled" /></template>
<style>
.g61bstb3g {
  fill: currentColor;
  d: path("M7.646 1.146a.5.5 0 0 1 .708 0c.261.262 1.408 1.45 2.493 3.003C11.917 5.68 13 7.665 13 9.5c0 1.78-.577 3.165-1.516 4.105C10.549 14.542 9.291 15 8 15s-2.549-.458-3.484-1.395C3.577 12.665 3 11.281 3 9.5c0-1.835 1.083-3.82 2.153-5.35a24 24 0 0 1 2.493-3.004");
}

</style>
