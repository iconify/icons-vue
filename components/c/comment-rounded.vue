<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n7h3w9j8b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:comment-rounded" /></template>
<style>
.n7h3w9j8b {
  fill: currentColor;
  d: path("M7 13.5h10q.213 0 .356-.144t.144-.357t-.144-.356T17 12.5H7q-.213 0-.356.144t-.144.357t.144.356T7 13.5m0-3h10q.213 0 .356-.144t.144-.357t-.144-.356T17 9.5H7q-.213 0-.356.144t-.144.357t.144.356T7 10.5m0-3h10q.213 0 .356-.144t.144-.357t-.144-.356T17 6.5H7q-.213 0-.356.144t-.144.357t.144.356T7 7.5M4.616 17q-.691 0-1.153-.462T3 15.385V4.615q0-.69.463-1.153T4.615 3h14.77q.69 0 1.152.462T21 4.615v13.518q0 .534-.497.742t-.876-.171L17.923 17z");
}

</style>
