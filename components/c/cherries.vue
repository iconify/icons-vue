<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="msiopc6tk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:cherries" /></template>
<style>
.msiopc6tk {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M10.682 13.318q-1.035-1.035-2.408-1.257q.367-5.083 6.243-7.117q1.088 3.47 1.216 6.115q-1.377.221-2.415 1.259Q12 13.636 12 15.5t1.318 3.182T16.5 20t3.182-1.318T21 15.5t-1.318-3.182q-1.051-1.05-2.448-1.264q-.14-3.143-1.522-7.291q-.019-.055-.045-.106q-.03-.058-.069-.11t-.087-.096t-.103-.08t-.114-.061t-.124-.04q-.063-.015-.128-.019q-.066-.003-.13.004q-.065.008-.128.027h-.001q-7.63 2.29-8.013 8.772q-1.4.212-2.452 1.264Q3 14.636 3 16.5t1.318 3.182T7.5 21t3.182-1.318T12 16.5t-1.318-3.182");
}

</style>
