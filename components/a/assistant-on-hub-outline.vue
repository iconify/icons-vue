<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jdqo0bceh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:assistant-on-hub-outline" /></template>
<style>
.jdqo0bceh {
  fill: currentColor;
  d: path("M10.807 12.001q.23-.23.23-.54q0-.309-.23-.539t-.54-.23t-.539.23q-.23.23-.23.54t.23.539t.54.23t.539-.23m-3.46 0q.23-.23.23-.54q0-.309-.23-.539t-.54-.23t-.539.23q-.23.23-.23.54t.23.539t.54.23t.539-.23m6.386.23q.31 0 .539-.23t.23-.54t-.23-.539t-.54-.23t-.539.23q-.23.23-.23.54t.23.539t.54.23m3.999-.23q.23-.23.23-.54q0-.309-.23-.539t-.54-.23t-.539.23t-.23.54t.23.539t.54.23t.539-.23m-13.116 4.46h14.769q.23 0 .423-.192t.192-.423V7.077q0-.23-.192-.423q-.193-.193-.424-.193H4.616q-.231 0-.424.193Q4 6.846 4 7.077v8.77q0 .23.192.422t.423.193m7.385 3q-2.436 0-3.968-.29T6.5 18.427v-.965H4.616q-.691 0-1.153-.463T3 15.846V7.077q0-.69.463-1.153t1.152-.463h14.77q.69 0 1.152.463T21 7.077v8.77q0 .69-.463 1.152t-1.153.463H17.5v.965q0 .456-1.532.745q-1.532.29-3.968.29m0-8");
}

</style>
