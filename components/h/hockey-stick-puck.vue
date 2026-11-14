<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w9x7b5gnz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:hockey-stick-puck" /></template>
<style>
.w9x7b5gnz {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M16.65 3.625L9.161 16.606Q7.453 20 4 20h-.5q-2.25 0-2.25-2.25q0-.149.057-.287t.163-.243q.105-.106.243-.163T2 17q.074 0 .146.014q.073.015.141.043t.13.069t.113.094q.053.052.094.113t.069.13t.043.141t.014.146q0 .75.75.75H4q2.536 0 3.829-2.585l.021-.04l7.5-13q.037-.064.086-.119q.049-.056.107-.101q.059-.045.125-.078q.066-.032.138-.051q.071-.02.145-.024q.073-.005.147.004q.073.01.143.034q.07.023.134.06q.129.075.22.193t.129.263t.02.292q-.02.148-.094.277M17.5 14.5q-4.25 0-4.25 2.25v2.5q0 2.25 4.25 2.25t4.25-2.25v-2.5q0-2.25-4.25-2.25m-2.75 4.75v-.621Q15.775 19 17.5 19t2.75-.371v.621q0 .75-2.75.75t-2.75-.75");
}

</style>
