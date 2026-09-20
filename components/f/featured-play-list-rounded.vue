<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m-545wssb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:featured-play-list-rounded" /></template>
<style>
.m-545wssb {
  fill: currentColor;
  d: path("M7 12.5h7q.214 0 .357-.143T14.5 12t-.143-.357T14 11.5H7q-.213 0-.357.143T6.5 12t.143.357T7 12.5m0-3h7q.214 0 .357-.143T14.5 9t-.143-.357T14 8.5H7q-.213 0-.357.143T6.5 9t.143.357T7 9.5M4.616 19q-.691 0-1.153-.462T3 17.384V6.616q0-.691.463-1.153T4.615 5h14.77q.69 0 1.152.463T21 6.616v10.769q0 .69-.463 1.153T19.385 19z");
}

</style>
