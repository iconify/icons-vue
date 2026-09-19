<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="z0dut0agg"/><path class="sfckzbb0u"/><path class="grjvbubxy"/><path class="ocer7htkt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione:flag-for-solomon-islands" /></template>
<style>
.grjvbubxy {
  fill: var(--svg-color--ffe62e, #ffe62e);
  d: path("M3.5 41.5C4.2 43.4 5 45.2 6 47c1 1.7 2.2 3.4 3.5 4.9l50.9-29.4c-1.3-3.8-3.3-7.4-6-10.4z");
}

.ocer7htkt {
  fill: var(--svg-color--fff, #fff);
  d: path("m19 20.5l2 1.4l-.8-2.2l2-1.4h-2.4l-.8-2.2l-.8 2.2h-2.4l2 1.4l-.8 2.2zm-5.4-5.7l2 1.3l-.8-2.2l2-1.3h-2.4l-.8-2.2l-.8 2.2h-2.4l2 1.3l-.8 2.2zm10.8 0l2 1.3l-.8-2.2l2-1.3h-2.4l-.8-2.2l-.8 2.2h-2.5l2 1.3l-.7 2.2zM13.6 26.3l2 1.3l-.8-2.2l2-1.3h-2.4l-.8-2.2l-.8 2.2h-2.4l2 1.3l-.8 2.2zm10.8 0l2 1.3l-.8-2.2l2-1.3h-2.4l-.8-2.2l-.8 2.2h-2.5l2 1.3l-.7 2.2z");
}

.sfckzbb0u {
  fill: var(--svg-color--2a5f9e, #2a5f9e);
  d: path("M39.8 3C23.8-1.3 7.3 8.2 3 24.2c-1.6 5.9-1.3 11.9.5 17.3l3.7 1l4.5 1.2l40.5-23.4l1.2-4.5l1-3.7C50.7 7.8 45.7 4.6 39.8 3");
}

.z0dut0agg {
  fill: var(--svg-color--699635, #699635);
  d: path("m60.4 22.5l-8.2-2.2l-40.5 23.4l-2.2 8.2c3.8 4.3 8.8 7.5 14.7 9.1c16 4.3 32.5-5.2 36.7-21.2c1.7-5.9 1.4-11.9-.5-17.3");
}

</style>
