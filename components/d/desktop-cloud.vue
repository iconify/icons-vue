<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gm8zk0b4j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:desktop-cloud" /></template>
<style>
.gm8zk0b4j {
  fill: currentColor;
  d: path("M9 14h6.5q.839 0 1.42-.593t.58-1.432t-.596-1.42t-1.454-.58h-.27V9.86q-.045-1.218-.972-2.039T12 7q-.871 0-1.606.473T9.292 8.737l-.134.269l-.289.019q-1.007.05-1.688.759q-.681.708-.681 1.716q0 1.039.73 1.77T9 14m0 6v-1h2v-2H4.616q-.691 0-1.153-.462T3 15.385v-9.77q0-.69.463-1.152T4.615 4h14.77q.69 0 1.152.463T21 5.616v9.769q0 .69-.463 1.153T19.385 17H13v2h2v1z");
}

</style>
