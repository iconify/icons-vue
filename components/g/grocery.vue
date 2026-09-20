<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g_c714bjf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:grocery" /></template>
<style>
.g_c714bjf {
  fill: currentColor;
  d: path("M4.616 19q-.691 0-1.153-.462T3 17.384v-6.868q0-.2.076-.458t.151-.458l2.23-4.985h-.803q-.329 0-.51-.181t-.183-.511v-.23q0-.33.182-.511T4.653 3h5.693q.329 0 .51.182t.183.51v.231q0 .329-.182.51t-.51.182h-.805l2.497 5.647q-1.43.876-2.247 2.456t-.817 3.238q0 .75.179 1.559T9.696 19zM16 21q-2.077 0-3.538-1.461T11 16t1.462-3.538T16 11t3.539 1.462T21 16t-1.461 3.539T16 21m0-11.385q-.646-.173-1.073-.696T14.5 7.692t.427-1.227T16 5.77zq.173-.646.696-1.073t1.227-.427t1.227.427t.696 1.073z");
}

</style>
