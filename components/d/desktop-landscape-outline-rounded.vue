<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e8slw-7ki"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:desktop-landscape-outline-rounded" /></template>
<style>
.e8slw-7ki {
  fill: currentColor;
  d: path("M7.192 15.616h6.847q.348 0 .577-.23q.23-.23.23-.578v-2.846q0-.348-.23-.578t-.577-.23H7.192q-.348 0-.577.23q-.23.23-.23.578v2.846q0 .348.23.578t.577.23m1.934-6.473q.126.126.316.126h6.597q.296 0 .494.198q.198.199.198.495v2.365q0 .19.126.316t.316.126t.317-.126t.126-.316V9.962q0-.652-.463-1.115t-1.114-.462H9.442q-.19 0-.316.126T9 8.827t.126.316M4.616 19q-.691 0-1.153-.462T3 17.384V6.616q0-.691.463-1.153T4.615 5h14.77q.69 0 1.152.463T21 6.616v10.769q0 .69-.463 1.153T19.385 19zm0-1h14.769q.23 0 .423-.192t.192-.424V6.616q0-.231-.192-.424T19.385 6H4.615q-.23 0-.423.192T4 6.616v10.769q0 .23.192.423t.423.192M4 18V6z");
}

</style>
