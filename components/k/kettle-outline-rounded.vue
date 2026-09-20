<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hmbuf_bgf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:kettle-outline-rounded" /></template>
<style>
.hmbuf_bgf {
  fill: currentColor;
  d: path("M7 16.23V6.328L5.47 4.292q-.299-.403-.078-.848T6.116 3h10.101q.486 0 .827.341t.34.826V6h2q.667 0 1.141.475T21 7.615v5q0 .667-.475 1.141t-1.14.475h-2v2q0 .666-.475 1.14q-.474.475-1.14.475H8.615q-.667 0-1.141-.474Q7 16.897 7 16.23m1.616.615h7.153q.27 0 .442-.173q.174-.173.174-.442V4H6.48L8 5.973v10.258q0 .269.173.442t.443.173m8.769-3.615h2q.269 0 .442-.173t.173-.442v-5q0-.27-.173-.443T19.385 7h-2zm-4.351-7.192q-.265.269-.265.653v7.462q0 .384.265.654q.264.269.658.269t.659-.27t.265-.653V6.692q0-.384-.265-.653t-.659-.27t-.658.27M4.5 21q-.213 0-.356-.144T4 20.499t.144-.356T4.5 20h15q.213 0 .356.144t.144.357t-.144.356T19.5 21zm6.942-10.577");
}

</style>
