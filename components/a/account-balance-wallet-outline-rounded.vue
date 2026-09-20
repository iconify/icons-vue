<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zrtedlluu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:account-balance-wallet-outline-rounded" /></template>
<style>
.zrtedlluu {
  fill: currentColor;
  d: path("M5 17v2V5zm.616 3q-.672 0-1.144-.472T4 18.385V5.615q0-.67.472-1.143Q4.944 4 5.616 4h12.769q.67 0 1.143.472q.472.472.472 1.144v2.942h-1V5.616q0-.27-.173-.443T18.385 5H5.615q-.269 0-.442.173T5 5.616v12.769q0 .269.173.442t.443.173h12.769q.269 0 .442-.173t.173-.442v-2.943h1v2.943q0 .67-.472 1.143q-.472.472-1.143.472zm8-4q-.672 0-1.144-.472T12 14.385v-4.77q0-.67.472-1.143Q12.944 8 13.616 8h5.769q.67 0 1.143.472q.472.472.472 1.144v4.769q0 .67-.472 1.143q-.472.472-1.143.472zm5.769-1q.269 0 .442-.173t.173-.442v-4.77q0-.269-.173-.442T19.385 9h-5.77q-.269 0-.442.173T13 9.616v4.769q0 .269.173.442t.443.173zm-2.322-1.937q.437-.438.437-1.063t-.437-1.062T16 10.5t-1.062.438T14.5 12t.438 1.063T16 13.5t1.063-.437");
}

</style>
