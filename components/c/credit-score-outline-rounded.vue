<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="isdw9cbfv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:credit-score-outline-rounded" /></template>
<style>
.isdw9cbfv {
  fill: currentColor;
  d: path("M4 8.808h16V6.616q0-.231-.192-.424T19.385 6H4.615q-.23 0-.423.192T4 6.616zM3 6.616q0-.691.463-1.153T4.615 5h14.77q.69 0 1.152.463T21 6.616v3.769q0 .348-.23.578t-.578.23H4v6.192q0 .23.192.423t.423.192h4.158q.214 0 .357.143t.143.357t-.143.357t-.357.143H4.615q-.69 0-1.153-.462T3 17.384zm1 0V18v-3.926v1.674V6zm10.642 13.6q-.142 0-.288-.056t-.277-.187l-2.638-2.638q-.141-.14-.153-.342t.153-.366q.159-.16.35-.16q.192 0 .357.16l2.496 2.485l5.33-5.33q.145-.145.346-.152t.367.159q.16.165.162.353q.003.189-.162.354l-5.477 5.477q-.131.13-.268.187q-.136.055-.298.055");
}

</style>
