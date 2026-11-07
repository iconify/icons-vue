<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="skserhbiw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:looks-9" /></template>
<style>
.skserhbiw {
  fill: currentColor;
  d: path("M5.616 20q-.691 0-1.153-.462T4 18.384V5.616q0-.691.463-1.153T5.616 4h12.769q.69 0 1.153.463T20 5.616v12.769q0 .69-.462 1.153T18.384 20zm4.884-3.5h2.385q.69 0 1.152-.462t.463-1.153v-5.77q0-.69-.462-1.152T12.885 7.5h-1.77q-.69 0-1.152.463T9.5 9.116v1.769q0 .69.463 1.153t1.153.462H13.5v2.385q0 .269-.173.442t-.442.173H10.5zm3-5h-2.384q-.27 0-.443-.173t-.173-.442v-1.77q0-.269.173-.442t.443-.173h1.769q.269 0 .442.173t.173.442z");
}

</style>
