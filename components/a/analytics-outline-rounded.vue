<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qams5xhas"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:analytics-outline-rounded" /></template>
<style>
.qams5xhas {
  fill: currentColor;
  d: path("M7.874 12.143q-.143.144-.143.357V16q0 .214.143.357t.357.143t.357-.143T8.73 16v-3.5q0-.213-.144-.357T8.231 12t-.357.143m7.539-5q-.144.144-.144.357V16q0 .214.144.357t.356.143t.357-.143t.143-.357V7.5q0-.213-.143-.357T15.769 7t-.357.143m-3.769 7q-.143.144-.143.357V16q0 .214.143.357T12 16.5t.357-.143T12.5 16v-1.5q0-.213-.143-.357T12 14t-.357.143M5.616 20q-.691 0-1.153-.462T4 18.384V5.616q0-.691.463-1.153T5.616 4h12.769q.69 0 1.153.463T20 5.616v12.769q0 .69-.462 1.153T18.384 20zm0-1h12.769q.23 0 .423-.192t.192-.424V5.616q0-.231-.192-.424T18.384 5H5.616q-.231 0-.424.192T5 5.616v12.769q0 .23.192.423t.423.192M5 5v14zm7.357 6.357q.143-.143.143-.357t-.143-.357T12 10.5t-.357.143T11.5 11t.143.357t.357.143t.357-.143");
}

</style>
