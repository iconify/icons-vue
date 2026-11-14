<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tcogwhb2w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:hiring-manager" /></template>
<style>
.tcogwhb2w {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M5.818 5.068Q4.5 6.386 4.5 8.25t1.318 3.182T9 12.75t3.182-1.318T13.5 8.25t-1.318-3.182T9 3.75T5.818 5.068M17.5 4.75q-3.25 0-3.25 3.25t3.25 3.25q1.095 0 1.821-.369l1.649 1.649q.052.053.113.094t.13.069t.141.043t.146.014t.146-.014q.073-.015.141-.043t.13-.069q.061-.041.113-.094q.106-.105.163-.243T22.25 12t-.057-.287t-.163-.243l-1.649-1.649q.369-.726.369-1.821q0-3.25-3.25-3.25M1.75 20q0-2.427 2.213-4.015Q6.03 14.5 9 14.5q-1.38.001-1.619 1.359l-.484 2.742q-.203 1.153.625 1.981l.198.198q1.28 1.28 2.56 0l.199-.198q.827-.828.624-1.981l-.484-2.742Q10.38 14.501 9 14.5q2.97 0 5.037 1.485Q16.25 17.573 16.25 20q0 1.75-1.75 1.75h-11q-1.75 0-1.75-1.75");
}

</style>
