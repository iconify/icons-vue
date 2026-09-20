<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aacf5yksc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:folder-eye" /></template>
<style>
.aacf5yksc {
  fill: currentColor;
  d: path("M4.616 19q-.691 0-1.153-.462T3 17.384V6.616q0-.691.463-1.153T4.615 5h4.981l2 2h7.789q.69 0 1.153.463T21 8.616v5.763q-1.083-.762-2.312-1.224t-2.553-.463q-2.922 0-5.246 1.946Q8.566 16.586 7.262 19zm11.519 3q-1.833 0-3.383-.94t-2.483-2.521q.933-1.581 2.483-2.522t3.382-.94t3.383.94T22 18.538q-.933 1.581-2.483 2.521q-1.55.941-3.382.941m1.255-2.206q.514-.513.514-1.256t-.514-1.255t-1.256-.514q-.742 0-1.255.514q-.513.513-.513 1.255t.513 1.256t1.256.514t1.255-.514m-1.962-.549q-.294-.293-.294-.707t.294-.706q.293-.294.706-.294q.414 0 .707.294t.293.706t-.293.707t-.707.293t-.706-.293");
}

</style>
