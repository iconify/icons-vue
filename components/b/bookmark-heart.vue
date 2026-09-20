<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zbe05mbqo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:bookmark-heart" /></template>
<style>
.zbe05mbqo {
  fill: currentColor;
  d: path("M12 13.742q1.102-1.001 1.755-1.649q.653-.647 1.02-1.1t.489-.81q.12-.354.12-.752q0-.765-.543-1.32q-.545-.553-1.31-.553q-.448 0-.859.183q-.41.184-.672.501q-.261-.317-.67-.5q-.407-.184-.86-.184q-.766 0-1.31.554q-.544.553-.544 1.319q0 .398.108.74q.109.343.476.796q.367.454 1.027 1.111T12 13.742M6 19.5V5.616q0-.691.463-1.153T7.616 4h8.769q.69 0 1.153.463T18 5.616V19.5l-6-2.577z");
}

</style>
