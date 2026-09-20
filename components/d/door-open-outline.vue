<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l5t9orzqv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:door-open-outline" /></template>
<style>
.l5t9orzqv {
  fill: currentColor;
  d: path("M11 12.77q.329 0 .549-.23t.22-.54q0-.329-.22-.549t-.549-.22q-.31 0-.54.22t-.23.549q0 .31.23.54t.54.23M7 20v-1l7-.692V6.452q0-.567-.37-.983q-.368-.415-.91-.465L7.615 4.5v-1l5.23.516q.927.103 1.54.794Q15 5.5 15 6.427v12.762zm-2.539 0v-1H6V5.116q0-.697.472-1.156q.472-.46 1.144-.46h8.769q.696 0 1.156.46T18 5.116V19h1.539v1zM7 19h10V5.116q0-.27-.173-.443t-.442-.173h-8.77q-.269 0-.442.173T7 5.116z");
}

</style>
