<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="axra3x72e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:feed-rounded" /></template>
<style>
.axra3x72e {
  fill: currentColor;
  d: path("M5.616 20q-.691 0-1.153-.462T4 18.384V5.616q0-.691.463-1.153T5.616 4h9.29q.323 0 .628.13q.305.132.522.349l3.465 3.465q.218.218.348.522q.131.305.131.628v9.29q0 .691-.462 1.154T18.384 20zM15 5v3.192q0 .348.23.578t.578.23H19zm1 11q.214 0 .357-.143t.143-.357t-.143-.357T16 15H8q-.213 0-.357.143T7.5 15.5t.143.357T8 16zm-4.5-7q.214 0 .357-.143T12 8.5t-.143-.357T11.5 8H8q-.213 0-.357.143T7.5 8.5t.143.357T8 9zm4.5 3.5q.214 0 .357-.143T16.5 12t-.143-.357T16 11.5H8q-.213 0-.357.143T7.5 12t.143.357T8 12.5z");
}

</style>
