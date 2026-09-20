<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v-8y_0bma"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:headset-mic-rounded" /></template>
<style>
.v-8y_0bma {
  fill: currentColor;
  d: path("M5.616 19q-.691 0-1.153-.462T4 17.384V11q0-1.658.626-3.113t1.716-2.545t2.546-1.716T12 3t3.113.626t2.545 1.716t1.716 2.546T20 11v8.77q0 .69-.462 1.152q-.463.463-1.153.463H12.5q-.213 0-.357-.144q-.143-.143-.143-.356q0-.214.143-.357q.143-.144.357-.144h5.885q.269 0 .442-.173q.173-.172.173-.442V19h-1.461q-.672 0-1.144-.472t-.472-1.144v-2.922q0-.671.472-1.144t1.144-.472H19V11q0-2.9-2.05-4.95T12 4T7.05 6.05T5 11v1.846h1.462q.67 0 1.143.472q.472.472.472 1.143v2.923q0 .672-.472 1.144T6.46 19z");
}

</style>
