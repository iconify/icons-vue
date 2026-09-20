<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cb3rbpbiy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:calendar-lock-outline-rounded" /></template>
<style>
.cb3rbpbiy {
  fill: currentColor;
  d: path("M5.616 21q-.691 0-1.153-.462T4 19.385V6.615q0-.69.463-1.152T5.616 5h1.769V3.308q0-.233.153-.386t.385-.153t.386.153t.153.386V5h7.154V3.27q0-.214.143-.358t.357-.143t.356.143t.144.357V5h1.769q.69 0 1.153.463T20 6.616v4.769q0 .213-.143.356t-.357.144t-.357-.144t-.143-.356v-.77H5v8.77q0 .23.192.423t.423.192h6.981q.214 0 .357.143q.143.144.143.357t-.143.357t-.357.143zM5 9.615h14v-3q0-.23-.192-.423T18.384 6H5.616q-.231 0-.424.192T5 6.616zm0 0V6zM16.37 21q-.35 0-.62-.27t-.27-.618v-2.8q0-.35.27-.6t.62-.25h.11v-1q0-.749.511-1.259t1.259-.51t1.259.51t.51 1.258v1h.112q.35 0 .61.25q.259.25.259.6v2.8q0 .35-.26.62q-.26.269-.61.269zm.88-4.538h2v-1q0-.425-.288-.713t-.712-.288t-.712.288t-.288.713z");
}

</style>
