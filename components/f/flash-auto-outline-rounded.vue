<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nnpruphjq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:flash-auto-outline-rounded" /></template>
<style>
.nnpruphjq {
  fill: currentColor;
  d: path("m16.975 8.7l-.625 1.825q-.075.2-.262.338t-.413.137q-.375 0-.587-.312T15 10.025L17.7 2.8q.125-.35.438-.55t.662-.2q.375 0 .688.238t.437.587l2.725 7.175q.125.35-.075.65T22 11q-.225 0-.425-.137T21.3 10.5l-.625-1.8zm.45-1.3h2.75L18.85 3.65h-.05zM7 15.6l3.2-4.6H7.35l2-7H4v8h3zm-1.85 4.463Q5 19.875 5 19.6V14H4q-.825 0-1.412-.587T2 12V4q0-.825.588-1.412T4 2h5.85q.8 0 1.288.625T11.425 4L10 9h1.125q.9 0 1.338.8t-.088 1.55l-6 8.675q-.15.225-.387.3t-.463 0t-.375-.262M7 12H4z");
}

</style>
