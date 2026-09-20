<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qczski8-x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:chat-info-rounded" /></template>
<style>
.qczski8-x {
  fill: currentColor;
  d: path("M12 6.616q.262 0 .439-.177T12.615 6t-.177-.438T12 5.385t-.438.177t-.177.438t.177.439t.438.177m.357 7.663q.143-.143.143-.356V8.846q0-.212-.144-.356t-.357-.144t-.356.144t-.143.356v5.077q0 .213.144.356t.357.144t.356-.144M6.077 17l-1.704 1.704q-.379.379-.876.171T3 18.133V4.616q0-.691.463-1.153T4.615 3h14.77q.69 0 1.152.463T21 4.616v10.769q0 .69-.463 1.153T19.385 17z");
}

</style>
