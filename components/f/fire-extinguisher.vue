<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vs3_iw0jl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:fire-extinguisher" /></template>
<style>
.vs3_iw0jl {
  fill: currentColor;
  d: path("M7.994 16.23v-4h8v4zm5.155-9.465q.46-.461.46-1.155q0-.695-.46-1.155t-1.155-.46t-1.154.46q-.461.46-.461 1.154q0 .695.46 1.155q.461.461 1.155.461t1.155-.46M8.037 11.23q.134-1.154.88-2.059q.744-.905 1.881-1.264q-.41-.2-.737-.54q-.328-.34-.498-.78l-3.102-.594v-.769l3.103-.594q.298-.731.952-1.187q.655-.455 1.478-.455q.556 0 1.043.225t.847.594l3.039-.602v4.808l-3.038-.602q-.146.165-.319.277q-.172.111-.376.219q1.137.34 1.87 1.251q.732.912.892 2.072zM9.609 21q-.69 0-1.152-.462t-.463-1.153V17.23h8v2.154q0 .69-.462 1.153T14.379 21z");
}

</style>
