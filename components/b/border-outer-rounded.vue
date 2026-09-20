<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rstgqccvx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:border-outer-rounded" /></template>
<style>
.rstgqccvx {
  fill: currentColor;
  d: path("M11.566 8.741q-.182-.182-.182-.433q0-.252.182-.434T12 7.692t.434.182t.182.434t-.182.433t-.434.182t-.434-.182m-3.692 3.693q-.182-.182-.182-.434t.182-.434t.434-.182t.433.182t.182.434t-.182.434t-.433.182t-.434-.182m3.692 0q-.182-.182-.182-.434t.182-.434t.434-.182t.434.182t.182.434t-.182.434t-.434.182t-.434-.182m3.693 0q-.182-.182-.182-.434t.182-.434t.433-.182t.434.182t.182.434t-.182.434t-.434.182t-.433-.182m-3.693 3.692q-.182-.182-.182-.434q0-.251.182-.433t.434-.182t.434.182t.182.433t-.182.434t-.434.182t-.434-.182M5.616 19h12.769q.269 0 .442-.173t.173-.442V5.615q0-.269-.173-.442T18.385 5H5.615q-.269 0-.442.173T5 5.616v12.769q0 .269.173.442t.443.173m0 1q-.672 0-1.144-.472T4 18.385V5.615q0-.67.472-1.143Q4.944 4 5.616 4h12.769q.67 0 1.143.472q.472.472.472 1.144v12.769q0 .67-.472 1.143q-.472.472-1.143.472z");
}

</style>
