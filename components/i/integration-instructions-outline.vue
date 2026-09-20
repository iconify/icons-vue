<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gnl5c0bci"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:integration-instructions-outline" /></template>
<style>
.gnl5c0bci {
  fill: currentColor;
  d: path("m9.6 14.87l.708-.72L8.158 12l2.15-2.15l-.708-.72L6.73 12zm4.8 0L17.27 12L14.4 9.13l-.708.72l2.15 2.15l-2.15 2.15zM5.616 20q-.672 0-1.144-.472T4 18.385V5.615q0-.67.472-1.143Q4.944 4 5.616 4h4.7q-.137-.766.366-1.383Q11.184 2 12 2q.835 0 1.338.617T13.685 4h4.7q.67 0 1.143.472q.472.472.472 1.144v12.769q0 .67-.472 1.143q-.472.472-1.143.472zm0-1h12.769q.23 0 .423-.192t.192-.424V5.616q0-.231-.192-.424T18.384 5H5.616q-.231 0-.424.192T5 5.616v12.769q0 .23.192.423t.423.192m6.923-14.77q.212-.213.212-.538t-.212-.537T12 2.942t-.537.213t-.213.537t.213.538t.537.212t.538-.212M5 19V5z");
}

</style>
