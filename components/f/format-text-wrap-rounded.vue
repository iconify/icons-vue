<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bq7qvrbgw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:format-text-wrap-rounded" /></template>
<style>
.bq7qvrbgw {
  fill: currentColor;
  d: path("M5.143 18.857Q5 18.714 5 18.5v-13q0-.213.143-.357T5.5 5t.357.143T6 5.5v13q0 .214-.143.357T5.5 19t-.357-.143m13 0Q18 18.714 18 18.5v-13q0-.213.143-.357T18.5 5t.357.143T19 5.5v13q0 .214-.143.357T18.5 19t-.357-.143m-7.634-2.378l-1.913-1.913q-.242-.243-.242-.566t.242-.565l1.938-1.914q.141-.14.342-.143t.347.143q.14.14.14.345q0 .203-.14.344l-1.29 1.29h2.798q1.056 0 1.778-.722T15.23 11t-.722-1.778T12.73 8.5H8.269q-.213 0-.357-.143T7.77 8t.143-.357t.357-.143h4.462q1.458 0 2.479 1.021Q16.23 9.542 16.23 11t-1.02 2.479t-2.48 1.021H9.934l1.29 1.29q.14.14.14.342t-.14.347q-.146.165-.357.156q-.21-.01-.356-.156");
}

</style>
