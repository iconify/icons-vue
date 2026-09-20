<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f1yzq5g8m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:add-column-left-outline-rounded" /></template>
<style>
.f1yzq5g8m {
  fill: currentColor;
  d: path("M13.442 19h5.943q.269 0 .442-.173t.173-.442V5.615q0-.269-.173-.442T19.385 5h-5.943zm-6.826 1q-.667 0-1.141-.475T5 18.386v-1q0-.213.144-.357t.357-.143t.356.143t.143.357v1q0 .269.173.442t.443.173h5.826V5H6.616q-.27 0-.443.173T6 5.616v1q0 .212-.144.356t-.357.143t-.356-.143T5 6.615v-1q0-.666.475-1.14T6.615 4h12.77q.666 0 1.14.475T21 5.615v12.77q0 .666-.475 1.14t-1.14.475zm-1.473-5.644Q5 14.213 5 14v-1.5H3.5q-.213 0-.356-.144T3 11.999t.144-.356t.356-.143H5V10q0-.213.144-.356t.357-.144t.356.144T6 10v1.5h1.5q.213 0 .356.144t.144.357t-.144.356t-.356.143H6V14q0 .213-.144.356t-.357.144t-.356-.144m8.3-2.356h-1zm0 0");
}

</style>
