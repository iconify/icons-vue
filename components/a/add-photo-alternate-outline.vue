<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n6ijwx4ua"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:add-photo-alternate-outline" /></template>
<style>
.n6ijwx4ua {
  fill: currentColor;
  d: path("M5.616 20q-.691 0-1.153-.462T4 18.384V5.616q0-.691.463-1.153T5.616 4h7v1h-7q-.27 0-.443.173T5 5.616v12.769q0 .269.173.442t.443.173h12.769q.269 0 .442-.173t.173-.443v-7h1v7q0 .691-.462 1.153T18.384 20zm1.153-3.616h10.462L14 12.077l-3 3.789l-2-2.404zM17 9V7h-2V6h2V4h1v2h2v1h-2v2z");
}

</style>
