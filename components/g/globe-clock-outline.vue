<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pg79yxbsy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:globe-clock-outline" /></template>
<style>
.pg79yxbsy {
  fill: currentColor;
  d: path("M15.507 3.709q1.643.709 2.859 1.924t1.925 2.857T21 12v.217q-.244-.152-.484-.286q-.241-.135-.522-.233q-.084-2.379-1.419-4.326T15 4.562V5q0 .825-.587 1.413T13 7h-2v2q0 .425-.288.713T10 10H8v2h6.598q-1.511.829-2.44 2.31q-.927 1.482-.927 3.306v.192q0 .096.019.192H11q-.825 0-1.412-.587T9 16v-1l-4.8-4.8q-.075.45-.137.9T4 12q0 3.221 2.21 5.557q2.21 2.335 5.507 2.437q.09.283.22.522t.28.484H12q-1.868 0-3.51-.708t-2.857-1.924t-1.924-2.856T3 12.003t.709-3.51Q4.417 6.85 5.63 5.634t2.857-1.925T11.997 3t3.51.709M14.78 20.45q-1.164-1.164-1.164-2.835t1.164-2.836t2.836-1.164q1.67 0 2.835 1.164t1.165 2.836q0 1.67-1.165 2.835t-2.835 1.165q-1.672 0-2.836-1.165m4.486-.64l.546-.545L18 17.46v-2.73h-.77v3.046z");
}

</style>
