<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y6vklhbjk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:desktop-portrait-rounded" /></template>
<style>
.y6vklhbjk {
  fill: currentColor;
  d: path("M11.962 17.616h2.846q.348 0 .578-.23t.23-.578V9.962q0-.348-.23-.578t-.578-.23h-2.846q-.348 0-.578.23t-.23.578v6.846q0 .348.23.578t.578.23m-2.819-2.742q.126-.126.126-.316V7.962q0-.296.198-.495q.199-.198.495-.198h2.365q.19 0 .316-.126t.126-.316t-.126-.317t-.316-.126H9.962q-.633 0-1.105.473q-.472.472-.472 1.104v6.597q0 .19.126.316t.316.126t.316-.126M19 19.384q0 .691-.462 1.154T17.384 21H6.616q-.691 0-1.153-.462T5 19.385V4.615q0-.69.463-1.152T6.616 3h10.769q.69 0 1.153.463T19 4.616z");
}

</style>
