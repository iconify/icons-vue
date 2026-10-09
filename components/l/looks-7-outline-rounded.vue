<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="knqjywb4l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:looks-7-outline-rounded" /></template>
<style>
.knqjywb4l {
  fill: currentColor;
  d: path("M5.616 20q-.691 0-1.153-.462T4 18.384V5.616q0-.691.463-1.153T5.616 4h12.769q.69 0 1.153.463T20 5.616v12.769q0 .69-.462 1.153T18.384 20zm0-1h12.769q.23 0 .423-.192t.192-.424V5.616q0-.231-.192-.424T18.384 5H5.616q-.231 0-.424.192T5 5.616v12.769q0 .23.192.423t.423.192M5 5v14zm8.462 3.5l-1.854 7.377q-.068.238.088.43t.42.193q.176 0 .301-.104t.181-.275l1.833-7.275l.05-.215q.019-.09.019-.216q0-.378-.282-.647t-.66-.268H10q-.213 0-.357.143T9.5 8t.143.357T10 8.5z");
}

</style>
