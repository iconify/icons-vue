<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tusaxqjfm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:h-plus-mobiledata-badge-outline-rounded" /></template>
<style>
.tusaxqjfm {
  fill: currentColor;
  d: path("M3.616 20q-.691 0-1.153-.462T2 18.384V5.616q0-.691.463-1.153T3.616 4h16.769q.69 0 1.153.463T22 5.616v12.769q0 .69-.462 1.153T20.385 20zm0-1h16.769q.23 0 .423-.192t.192-.424V5.616q0-.231-.192-.424T20.385 5H3.615q-.23 0-.423.192T3 5.616v12.769q0 .23.192.423t.423.192M3 19V5zm3.308-6.5h4.615V16q0 .214.143.357t.357.143t.357-.143t.143-.357V8q0-.213-.143-.357t-.357-.143t-.357.143t-.143.357v3.5H6.308V8q0-.213-.143-.357T5.808 7.5t-.357.143T5.308 8v8q0 .214.143.357t.357.143t.357-.143t.143-.357zm9.384 0V14q0 .214.144.357t.356.143t.357-.143t.143-.357v-1.5h1.5q.214 0 .357-.143t.143-.357t-.143-.357t-.357-.143h-1.5V10q0-.213-.143-.357t-.357-.143t-.356.143t-.144.357v1.5h-1.5q-.213 0-.356.143t-.144.357t.144.357t.356.143z");
}

</style>
