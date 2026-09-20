<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cvn8vymls"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:ios-share-outline" /></template>
<style>
.cvn8vymls {
  fill: currentColor;
  d: path("M6.616 21q-.691 0-1.153-.462T5 19.385v-8.77q0-.69.463-1.152T6.616 9H8.73v1H6.616q-.231 0-.424.192T6 10.616v8.769q0 .23.192.423t.423.192h10.77q.23 0 .423-.192t.192-.423v-8.77q0-.23-.192-.423T17.384 10H15.27V9h2.115q.691 0 1.153.463T19 10.616v8.769q0 .69-.463 1.153T17.385 21zm4.884-5.5V4.614l-2.1 2.1L8.692 6L12 2.692L15.308 6l-.708.714l-2.1-2.1V15.5z");
}

</style>
