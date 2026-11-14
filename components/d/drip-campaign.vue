<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zxvyu1pnv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:drip-campaign" /></template>
<style>
.zxvyu1pnv {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M10.452 1.988q.017-.019.036-.036q.109-.102.249-.154t.289-.048q.149.006.285.067t.237.171q6.474 6.936 7.128 11.512H16q-3.5 0-3.5 3.5v2.5q0 1.582.715 2.449q-1.045.301-2.215.301q-3.21 0-5.48-2.27T3.25 14.5q0-4.796 7.202-12.512M20.5 14.75H16q-2.25 0-2.25 2.25v2.5q0 2.25 2.25 2.25h4.5q2.25 0 2.25-2.25V17q0-2.25-2.25-2.25m-2.25 3.054l-2.02-1.554h4.04zm-3 1.696v-2.111l2.543 1.955q.049.038.103.067t.112.049q.059.02.12.03q.06.01.122.01t.122-.01q.061-.01.12-.03t.112-.049q.054-.029.103-.067l2.543-1.955V19.5q0 .75-.75.75H16q-.75 0-.75-.75");
}

</style>
