<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kxn9izbbz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:difference-rounded" /></template>
<style>
.kxn9izbbz {
  fill: currentColor;
  d: path("M13 8.5V10q0 .213.144.356t.357.144t.356-.144T14 10V8.5h1.5q.213 0 .356-.144T16 7.999t-.144-.356T15.5 7.5H14V6q0-.213-.144-.356t-.357-.144t-.356.144T13 6v1.5h-1.5q-.213 0-.356.144T11 8.001t.144.356t.356.143zm-1.5 6h4q.213 0 .356-.144t.144-.357t-.144-.356t-.356-.143h-4q-.213 0-.356.144t-.144.357t.144.356t.356.143M8.616 18q-.691 0-1.153-.462T7 16.384V3.616q0-.691.463-1.153T8.616 2h6.213q.332 0 .632.13t.518.349L19.52 6.02q.218.218.348.518t.131.632v9.214q0 .69-.462 1.153T18.384 18zm-4 4q-.691 0-1.153-.462T3 20.385V8.5q0-.213.144-.356T3.501 8t.356.144T4 8.5v11.885q0 .23.192.423t.423.192H13.5q.213 0 .356.144t.144.357t-.144.356T13.5 22z");
}

</style>
