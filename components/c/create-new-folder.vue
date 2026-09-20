<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h0fmojvaq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:create-new-folder" /></template>
<style>
.h0fmojvaq {
  fill: currentColor;
  d: path("M14.5 15.5h1v-2h2v-1h-2v-2h-1v2h-2v1h2zM4.616 19q-.691 0-1.153-.462T3 17.384V6.616q0-.691.463-1.153T4.61 5h4.985l2 2h7.789q.69 0 1.153.463T21 8.616v8.769q0 .69-.462 1.153T19.385 19z");
}

</style>
