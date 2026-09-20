<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m35fjbcmu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:breaking-news-alt-1-rounded" /></template>
<style>
.m35fjbcmu {
  fill: currentColor;
  d: path("M7.27 16.5h3.46q.213 0 .357-.144t.144-.357t-.144-.356t-.356-.143H7.269q-.212 0-.356.144t-.144.357t.144.356t.356.143m0-4h3.462q.212 0 .356-.144t.144-.357t-.144-.356t-.356-.143H7.269q-.212 0-.356.144t-.144.357t.144.356t.356.143m9.105-4.856q-.143.143-.143.356v4q0 .213.144.356t.357.144t.356-.144t.143-.356V8q0-.213-.144-.356q-.144-.144-.357-.144t-.356.144M7.269 8.5h3.462q.212 0 .356-.144t.144-.357t-.144-.356t-.356-.143H7.269q-.212 0-.356.144t-.144.357t.144.356t.356.143M4.616 20q-.691 0-1.153-.462T3 18.384V5.616q0-.691.463-1.153T4.615 4h14.77q.69 0 1.152.463T21 5.616v12.769q0 .69-.463 1.153T19.385 20zm12.472-3.644q.143-.144.143-.357t-.144-.356t-.357-.143t-.356.144t-.143.357t.144.356t.356.143t.356-.144");
}

</style>
