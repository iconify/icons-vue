<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<defs><linearGradient id="SVGMx26Gc1s" x1="29.184%" x2="86.484%" y1="99.591%" y2=".354%"><stop offset="41.47%" class="qfxn8dbrz"/><stop offset="100%" class="q2qx6lbxd"/></linearGradient><linearGradient id="SVGnDtz5cFJ" x1="34.118%" x2="94.65%" y1="106.866%" y2="20.552%"><stop offset="41.47%" class="qfxn8dbrz"/><stop offset="100%" class="oei841b-f"/></linearGradient></defs><path fill="url(#SVGMx26Gc1s)" class="o_q4wjszc"/><path fill="url(#SVGnDtz5cFJ)" class="o9vnd0bqk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="logos:cyclejs" /></template>
<style>
.o_q4wjszc {
  d: path("M255.96 198.32c-.12 2.6-.84 5.16-2.16 7.48l-24.24 42a16.33 16.33 0 0 1-14.16 8.2H80.88c-5.84 0-11.24-3.12-14.16-8.16L2.2 136.2C.72 133.64 0 130.84 0 128s.56-5.8 2.28-8.68L66.76 8.16C69.68 3.12 75.08 0 80.88 0H215.4c5.84 0 11.24 3.12 14.16 8.16c0 0 23.32 38.2 25 40.92s1.4 6.16 1.4 8.96c0 2.4-.68 5.68-1.32 8.28s-20.16 81.72-20.16 81.72l-42.6-90.6h-87.32L63.68 128l40.88 70.56h87.28z");
}

.o9vnd0bqk {
  d: path("m224.84 127.96l29.6 62.76a16.31 16.31 0 0 1-.64 15.12l-61.92-7.24z");
}

.oei841b-f {
  stop-color: var(--svg-color--5a919b, #5a919b);
}

.q2qx6lbxd {
  stop-color: var(--svg-color--c8ff8c, #c8ff8c);
}

.qfxn8dbrz {
  stop-color: var(--svg-color--51d3d9, #51d3d9);
}

</style>
