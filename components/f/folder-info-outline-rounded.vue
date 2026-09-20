<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gmg5t4bxv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:folder-info-outline-rounded" /></template>
<style>
.gmg5t4bxv {
  fill: currentColor;
  d: path("M4 18V6v5.373v-.72zm.616 1q-.691 0-1.153-.462T3 17.384V6.616q0-.691.463-1.153T4.615 5h4.981l2 2h7.789q.69 0 1.153.463T21 8.616v2.598q0 .213-.143.353t-.357.14t-.357-.142t-.143-.357V8.616q0-.27-.173-.443T19.385 8h-8.19l-2-2h-4.58q-.269 0-.442.173T4 6.616v10.769q0 .269.173.442t.443.173h5.701q.214 0 .357.143t.143.357t-.143.357t-.357.143zm15.22-4.835Q21 15.329 21 17t-1.164 2.836T17 21t-2.835-1.164T13 17t1.165-2.835T17 13t2.836 1.165m-2.563 5.262q.112-.111.112-.273v-2.308q0-.162-.112-.273T17 16.462t-.273.111t-.111.273v2.308q0 .162.111.273t.273.112t.273-.112m.077-4.115q.15-.15.15-.35t-.15-.35t-.35-.15t-.35.15t-.15.35t.15.35t.35.15t.35-.15");
}

</style>
