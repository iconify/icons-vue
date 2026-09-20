<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y7lewww4y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:document-search-rounded" /></template>
<style>
.y7lewww4y {
  fill: currentColor;
  d: path("M18.496 18.496q.812-.811.812-1.996t-.812-1.996t-1.996-.812t-1.996.812t-.812 1.996t.812 1.996t1.996.812t1.996-.812m3.104 3.598q-.213 0-.354-.14l-2.423-2.442q-.487.388-1.08.592t-1.243.204q-1.586 0-2.697-1.111t-1.11-2.697t1.11-2.697t2.697-1.11t2.697 1.11t1.11 2.697q0 .65-.203 1.243t-.593 1.08l2.443 2.423q.14.14.14.354t-.14.354t-.354.14M5.616 21q-.691 0-1.153-.462T4 19.385V4.615q0-.69.463-1.152T5.616 3h7.213q.323 0 .628.13t.522.349L17.52 7.02q.217.218.348.522t.131.628v1.431q0 .354-.266.59q-.267.237-.64.17l-.294-.036q-.142-.018-.3-.018q-2.758 0-4.48 1.894t-1.724 4.323q0 .87.253 1.752q.253.883.828 1.698q.235.337.076.68q-.159.345-.532.345zM13 4v3.192q0 .348.23.578t.578.23H17zl4 4z");
}

</style>
