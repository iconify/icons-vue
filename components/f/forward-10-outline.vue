<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ifdxjlxsv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:forward-10-outline" /></template>
<style>
.ifdxjlxsv {
  fill: currentColor;
  d: path("M9.423 15.692v-4.5H8.039v-.884h2.269v5.384zm3.27 0q-.426 0-.713-.287t-.288-.713v-3.384q0-.425.288-.713t.712-.287h1.77q.425 0 .712.287t.288.713v3.384q0 .425-.288.713t-.712.287zm.115-.884h1.538q.116 0 .173-.058t.058-.173v-3.154q0-.115-.058-.173t-.173-.058h-1.538q-.116 0-.174.058t-.057.173v3.154q0 .115.057.173q.058.058.174.058m-3.926 5.566q-1.455-.626-2.542-1.713t-1.714-2.543T4 13t.626-3.118T6.34 7.34t2.542-1.714T12 5h.38l-1.664-1.666l.707-.719l2.885 2.866l-2.846 2.865l-.708-.719L12.38 6H12Q9.075 6 7.038 8.038T5 13t2.038 4.963T12 20t4.963-2.037T19 13h1q0 1.664-.626 3.118t-1.714 2.543t-2.542 1.713T12 21t-3.118-.626");
}

</style>
