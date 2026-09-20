<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wlk6rbcre"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:assignment-late-outline-rounded" /></template>
<style>
.wlk6rbcre {
  fill: currentColor;
  d: path("M12.434 16.318q.182-.181.182-.433t-.182-.434t-.434-.182t-.434.182t-.182.433q0 .252.182.434T12 16.5t.434-.182m-.077-2.923q.143-.143.143-.357V7.962q0-.214-.143-.357T12 7.46t-.357.144t-.143.356v5.078q0 .213.143.356t.357.144t.357-.144M5.616 20q-.672 0-1.144-.472T4 18.385V5.615q0-.67.472-1.143Q4.944 4 5.616 4h4.7q-.137-.766.366-1.383Q11.184 2 12 2q.835 0 1.338.617T13.685 4h4.7q.67 0 1.143.472q.472.472.472 1.144v12.769q0 .67-.472 1.143q-.472.472-1.143.472zm0-1h12.769q.23 0 .423-.192t.192-.424V5.616q0-.231-.192-.424T18.384 5H5.616q-.231 0-.424.192T5 5.616v12.769q0 .23.192.423t.423.192m6.923-14.77q.212-.213.212-.538t-.212-.537T12 2.942t-.537.213t-.213.537t.213.538t.537.212t.538-.212M5 19V5z");
}

</style>
