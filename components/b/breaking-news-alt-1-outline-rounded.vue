<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ocdefm17q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:breaking-news-alt-1-outline-rounded" /></template>
<style>
.ocdefm17q {
  fill: currentColor;
  d: path("M7.27 16.5h3.46q.214 0 .358-.143T11.23 16t-.143-.357t-.357-.143H7.269q-.213 0-.357.143T6.77 16t.143.357t.357.143m0-4h3.462q.213 0 .357-.143T11.23 12t-.143-.357t-.357-.143H7.269q-.213 0-.357.143T6.77 12t.143.357t.357.143m9.105-4.857q-.143.143-.143.357v4q0 .214.143.357t.357.143t.357-.143t.143-.357V8q0-.213-.144-.357t-.356-.143t-.357.143M7.269 8.5h3.462q.213 0 .357-.143T11.23 8t-.143-.357t-.357-.143H7.269q-.213 0-.357.143T6.77 8t.143.357t.357.143M4.616 20q-.691 0-1.153-.462T3 18.384V5.616q0-.691.463-1.153T4.615 4h14.77q.69 0 1.152.463T21 5.616v12.769q0 .69-.463 1.153T19.385 20zm0-1h14.769q.23 0 .423-.192t.192-.424V5.616q0-.231-.192-.424T19.385 5H4.615q-.23 0-.423.192T4 5.616v12.769q0 .23.192.423t.423.192M4 19V5zm13.088-2.643q.143-.144.143-.357t-.144-.357t-.356-.143t-.357.143t-.143.357t.143.357t.357.143t.356-.143");
}

</style>
