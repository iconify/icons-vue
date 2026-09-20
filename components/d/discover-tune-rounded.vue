<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bp42pllcm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:discover-tune-rounded" /></template>
<style>
.bp42pllcm {
  fill: currentColor;
  d: path("M14 8.5q-.213 0-.356-.144t-.144-.357t.144-.356T14 7.5h2.5V4q0-.213.144-.356t.357-.144t.356.144T17.5 4v3.5H20q.213 0 .356.144t.144.357t-.144.356T20 8.5zm2.643 11.856Q16.5 20.213 16.5 20v-8q0-.213.144-.356t.357-.144t.356.144t.143.356v8q0 .213-.144.356t-.357.144t-.356-.144m-10 0Q6.5 20.213 6.5 20v-3.5H4q-.213 0-.356-.144t-.144-.357t.144-.356T4 15.5h6q.213 0 .356.144t.144.357t-.144.356T10 16.5H7.5V20q0 .213-.144.356t-.357.144t-.356-.144m0-8Q6.5 12.213 6.5 12V4q0-.213.144-.356t.357-.144t.356.144T7.5 4v8q0 .213-.144.356t-.357.144t-.356-.144");
}

</style>
