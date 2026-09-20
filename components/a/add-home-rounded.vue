<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wspaqpmhq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:add-home-rounded" /></template>
<style>
.wspaqpmhq {
  fill: currentColor;
  d: path("M17.616 16.385V18.5q0 .154.115.27q.115.114.269.114t.27-.115q.114-.115.114-.269v-2.116H20.5q.154 0 .27-.111q.114-.111.114-.273t-.115-.273t-.269-.111h-2.116V13.5q0-.154-.115-.27q-.115-.114-.269-.114t-.27.115q-.114.115-.114.269v2.116H15.5q-.154 0-.27.111q-.114.112-.114.273t.115.273t.269.112zm-2.451 2.45Q14 17.672 14 16t1.165-2.835T18 12t2.836 1.165T22 16t-1.164 2.836T18 20t-2.835-1.164M5 16.385V8.308q0-.384.172-.727q.171-.344.474-.566l5.385-4.077q.423-.323.966-.323t.972.323l5.385 4.078q.303.222.474.566q.172.345.172.73v.425q0 .223-.17.385t-.413.132q-1.425-.108-2.812.414q-1.388.523-2.401 1.536q-1.177 1.177-1.665 2.727t-.198 3.144q.067.373-.154.649t-.57.276H6.616q-.667 0-1.141-.475T5 16.386");
}

</style>
