<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mjbt0l8ib"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:add-row-below-outline-rounded" /></template>
<style>
.mjbt0l8ib {
  fill: currentColor;
  d: path("M19 10.558V4.616q0-.27-.173-.443T18.385 4H5.615q-.269 0-.442.173T5 4.616v5.942zM5.616 19q-.667 0-1.141-.475T4 17.386V4.615q0-.666.475-1.14T5.615 3h12.77q.666 0 1.14.475T20 4.615v12.77q0 .666-.475 1.14t-1.14.475h-1q-.213 0-.357-.144t-.143-.357t.143-.356t.357-.143h1q.269 0 .442-.173t.173-.442v-5.827H5v5.827q0 .269.173.442t.443.173h1q.212 0 .356.144t.143.357t-.143.356t-.357.143zm6.027 1.856q-.143-.143-.143-.356V19H10q-.213 0-.356-.144t-.144-.357t.144-.356T10 18h1.5v-1.5q0-.213.144-.356t.357-.144t.356.144t.143.356V18H14q.213 0 .356.144t.144.357t-.144.356T14 19h-1.5v1.5q0 .213-.144.356t-.357.144t-.356-.144M12 10.558v1zm0 0");
}

</style>
