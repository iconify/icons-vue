<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tl6gd3koy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:bookmark-check-outline-rounded" /></template>
<style>
.tl6gd3koy {
  fill: currentColor;
  d: path("m10.95 11.175l-.725-.725q-.3-.275-.7-.275t-.7.3t-.3.7t.3.7l1.4 1.425q.3.3.713.3t.712-.3l3.525-3.55q.3-.3.3-.7t-.3-.7t-.7-.3t-.7.3zM12 18l-4.2 1.8q-1 .425-1.9-.162T5 17.975V5q0-.825.588-1.412T7 3h10q.825 0 1.413.588T19 5v12.975q0 1.075-.9 1.663t-1.9.162zm0-2.2l5 2.15V5H7v12.95zM12 5H7h10z");
}

</style>
