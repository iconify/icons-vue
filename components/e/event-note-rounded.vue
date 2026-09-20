<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q7j-0xbws"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:event-note-rounded" /></template>
<style>
.q7j-0xbws {
  fill: currentColor;
  d: path("M5.616 21q-.691 0-1.153-.462T4 19.385V6.615q0-.69.463-1.152T5.616 5h1.769V3.308q0-.233.153-.386t.385-.153t.386.153t.153.386V5h7.154V3.27q0-.214.143-.358t.357-.143t.356.143t.144.357V5h1.769q.69 0 1.153.463T20 6.616v12.769q0 .69-.462 1.153T18.384 21zm0-1h12.769q.23 0 .423-.192t.192-.424v-8.768H5v8.769q0 .23.192.423t.423.192M8 13.5q-.213 0-.357-.143T7.5 13t.143-.357T8 12.5h8q.214 0 .357.143T16.5 13t-.143.357T16 13.5zm0 4q-.213 0-.357-.143T7.5 17t.143-.357T8 16.5h5q.214 0 .357.143T13.5 17t-.143.357T13 17.5z");
}

</style>
