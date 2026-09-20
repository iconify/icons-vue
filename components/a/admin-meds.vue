<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vtw75xbzy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:admin-meds" /></template>
<style>
.vtw75xbzy {
  fill: currentColor;
  d: path("M8.566 15.429q.57.571 1.356.574t1.357-.568l1.727-1.727l-2.714-2.714l-1.726 1.727q-.553.552-.553 1.354t.553 1.354m6.868-6.858q-.57-.546-1.356-.562q-.786-.015-1.357.556L11 10.287L13.714 13l1.72-1.721q.572-.571.56-1.354t-.56-1.354M5.617 20q-.672 0-1.144-.472T4 18.385V5.615q0-.67.472-1.143Q4.944 4 5.616 4h4.7q-.137-.766.366-1.383Q11.184 2 12 2q.835 0 1.338.617T13.685 4h4.7q.67 0 1.143.472q.472.472.472 1.144v12.769q0 .67-.472 1.143q-.472.472-1.143.472zm6.922-15.77q.212-.213.212-.538t-.212-.537T12 2.942t-.537.213t-.213.537t.213.538t.537.212t.538-.212");
}

</style>
