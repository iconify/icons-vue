<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m-bsjqqyw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:grid-view-outline-rounded" /></template>
<style>
.m-bsjqqyw {
  fill: currentColor;
  d: path("M5 11q-.402 0-.701-.299T4 10V5q0-.402.299-.701T5 4h5q.402 0 .701.299T11 5v5q0 .402-.299.701T10 11zm0 9q-.402 0-.701-.299T4 19v-5q0-.402.299-.701T5 13h5q.402 0 .701.299T11 14v5q0 .402-.299.701T10 20zm9-9q-.402 0-.701-.299T13 10V5q0-.402.299-.701T14 4h5q.402 0 .701.299T20 5v5q0 .402-.299.701T19 11zm0 9q-.402 0-.701-.299T13 19v-5q0-.402.299-.701T14 13h5q.402 0 .701.299T20 14v5q0 .402-.299.701T19 20zM5 10h5V5H5zm9 0h5V5h-5zm0 9h5v-5h-5zm-9 0h5v-5H5zm5-9");
}

</style>
