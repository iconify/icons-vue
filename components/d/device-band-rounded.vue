<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pbx7n1qgg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:device-band-rounded" /></template>
<style>
.pbx7n1qgg {
  fill: currentColor;
  d: path("M10.48 21q-.69 0-1.152-.462t-.462-1.153V8.73h-.193q-.213 0-.357-.153q-.143-.153-.143-.347v-.962q0-.194.143-.347t.357-.153h.193V4.616q0-.691.462-1.153T10.481 3H13.5q.69 0 1.153.463t.463 1.153v2.153h.192q.213 0 .357.153q.143.153.143.347v.962q0 .194-.143.347q-.144.153-.357.153h-.192v10.654q0 .69-.463 1.153T13.5 21z");
}

</style>
