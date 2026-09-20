<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n3c-0yb9w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:ios-share-rounded" /></template>
<style>
.n3c-0yb9w {
  fill: currentColor;
  d: path("M6.616 21q-.691 0-1.153-.462T5 19.385v-8.77q0-.69.463-1.152T6.616 9H8.23q.213 0 .357.143t.143.357t-.143.357T8.23 10H6.616q-.231 0-.424.192T6 10.616v8.769q0 .23.192.423t.423.192h10.77q.23 0 .423-.192t.192-.423v-8.77q0-.23-.192-.423T17.384 10H15.77q-.213 0-.357-.143T15.27 9.5t.143-.357T15.77 9h1.615q.691 0 1.153.463T19 10.616v8.769q0 .69-.463 1.153T17.385 21zm5.027-5.643Q11.5 15.214 11.5 15V4.614L9.754 6.36q-.146.146-.344.153q-.199.006-.364-.16q-.16-.164-.162-.353t.162-.354l2.388-2.388q.132-.131.268-.184q.137-.053.298-.053t.298.053t.268.184l2.388 2.388q.14.14.15.342q.01.2-.15.366q-.166.165-.357.165t-.357-.165l-1.74-1.74V15q0 .214-.143.357T12 15.5t-.357-.143");
}

</style>
