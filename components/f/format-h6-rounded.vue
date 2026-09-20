<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eyn7petka"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:format-h6-rounded" /></template>
<style>
.eyn7petka {
  fill: currentColor;
  d: path("M3.643 16.356Q3.5 16.213 3.5 16V8q0-.213.144-.356t.357-.144t.356.144T4.5 8v3.5h5V8q0-.213.144-.356t.357-.144t.356.144T10.5 8v8q0 .213-.144.356t-.357.144t-.356-.144T9.5 16v-3.5h-5V16q0 .213-.144.356t-.357.144t-.356-.144m10.473.144q-.667 0-1.141-.475t-.475-1.14v-5.77q0-.666.475-1.14t1.14-.475H19q.213 0 .356.144t.144.357t-.144.356T19 8.5h-4.884q-.27 0-.443.173t-.173.443V11.5h4.385q.666 0 1.14.475t.475 1.14v1.77q0 .666-.475 1.14t-1.14.475zm-.616-4v2.385q0 .269.173.442t.443.173h3.769q.269 0 .442-.173t.173-.442v-1.77q0-.269-.173-.442t-.442-.173z");
}

</style>
