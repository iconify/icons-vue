<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="exws4f8dj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:folder-supervised-outline" /></template>
<style>
.exws4f8dj {
  fill: currentColor;
  d: path("M4 18V6v4.435V10zm.616 1q-.691 0-1.153-.462T3 17.384V6.616q0-.691.463-1.153T4.615 5h4.981l2 2h7.789q.69 0 1.153.463T21 8.616v2.294q-.238-.152-.479-.265q-.24-.112-.521-.21v-1.82q0-.269-.173-.442T19.385 8h-8.19l-2-2h-4.58q-.269 0-.442.173T4 6.616v10.769q0 .269.173.442t.443.173h6.748q.055.275.131.515t.186.485zm9.769 0v-.165q0-.876.869-1.355t2.438-.48t2.439.48t.869 1.355V19zm2.241-4.049q-.434-.434-.434-1.066t.434-1.067t1.066-.433t1.067.433t.433 1.067t-.433 1.066t-1.067.434t-1.066-.434");
}

</style>
