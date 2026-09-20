<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yaw57kbqb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:cake-add-outline-sharp" /></template>
<style>
.yaw57kbqb {
  fill: currentColor;
  d: path("M2 22v-8h2V8h6V6.55q-.45-.3-.725-.725T9 4.8q0-.375.15-.738T9.6 3.4L11 2l1.4 1.4q.3.3.45.662T13 4.8q0 .6-.275 1.025T12 6.55V8h6v6h2v8zm4-8h10v-4H6zm-2 6h14v-4H4zm2-6h10zm-2 6h14zm14-6H4zm1-6V6h-2V4h2V2h2v2h2v2h-2v2z");
}

</style>
