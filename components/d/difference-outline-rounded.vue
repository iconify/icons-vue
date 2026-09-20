<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zjeg3cb_j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:difference-outline-rounded" /></template>
<style>
.zjeg3cb_j {
  fill: currentColor;
  d: path("M13 8.5V10q0 .214.143.357t.357.143t.357-.143T14 10V8.5h1.5q.214 0 .357-.143T16 8t-.143-.357T15.5 7.5H14V6q0-.213-.143-.357T13.5 5.5t-.357.143T13 6v1.5h-1.5q-.213 0-.357.143T11 8t.143.357t.357.143zm-1.5 6h4q.214 0 .357-.143T16 14t-.143-.357t-.357-.143h-4q-.213 0-.357.143T11 14t.143.357t.357.143M8.616 18q-.691 0-1.153-.462T7 16.384V3.616q0-.691.463-1.153T8.616 2h6.213q.323 0 .628.13t.522.349L19.52 6.02q.218.218.348.522t.131.628v9.214q0 .69-.462 1.153T18.384 18zm0-1h9.769q.23 0 .423-.192t.192-.424V7l-4-4H8.616q-.231 0-.424.192T8 3.616v12.769q0 .23.192.423t.423.192m-4 5q-.69 0-1.153-.462T3 20.385V8.5q0-.213.143-.357T3.5 8t.357.143T4 8.5v11.885q0 .23.192.423t.423.192H13.5q.214 0 .357.143T14 21.5t-.143.357T13.5 22zM8 17V3z");
}

</style>
