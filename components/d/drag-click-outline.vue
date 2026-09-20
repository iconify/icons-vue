<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="otnr52bfq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:drag-click-outline" /></template>
<style>
.otnr52bfq {
  fill: currentColor;
  d: path("M12 18q-2.425 0-4.15-1.65T6 12.3l2.1.625q.325 1.35 1.4 2.213T12 16q1.65 0 2.825-1.175T16 12q0-1.425-.862-2.5t-2.213-1.4L12.3 6q2.4.125 4.05 1.85T18 12q0 2.5-1.75 4.25T12 18m-3.9 3.213q-1.825-.788-3.175-2.138T2.788 15.9T2 12v-.45q0-.225.05-.45l1.95.6v.3q0 3.35 2.325 5.675T12 20t5.675-2.325T20 12t-2.325-5.675T12 4h-.3l-.6-1.95q.225-.05.45-.05H12q2.075 0 3.9.788t3.175 2.137T21.213 8.1T22 12t-.788 3.9t-2.137 3.175t-3.175 2.138T12 22t-3.9-.788m2.425-8.712L6.25 8.225L5 12L2 2l10 3l-3.775 1.25l4.275 4.275z");
}

</style>
