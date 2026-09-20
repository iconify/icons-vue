<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jhgs04m_u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:document-dismiss-24-regular" /></template>
<style>
.jhgs04m_u {
  fill: currentColor;
  d: path("M6.5 12a5.5 5.5 0 1 1 0 11a5.5 5.5 0 0 1 0-11m5.629-10a2.25 2.25 0 0 1 1.59.658l2.812 2.81l2.808 2.813c.421.422.658.994.658 1.59v9.879a2.25 2.25 0 0 1-2.25 2.25l-6.557.001c.426-.444.79-.95 1.078-1.5l5.48-.001a.75.75 0 0 0 .75-.75l-.002-9.747H14.25a2.25 2.25 0 0 1-2.245-2.095L12 7.754L11.999 3.5H6.25a.75.75 0 0 0-.75.75l-.001 6.826a6.5 6.5 0 0 0-1.5.423L4 4.25A2.25 2.25 0 0 1 6.25 2zM8.854 15.147a.5.5 0 0 0-.708 0L6.5 16.793l-1.646-1.646a.5.5 0 1 0-.708.707L5.793 17.5l-1.647 1.646a.5.5 0 1 0 .708.707L6.5 18.208l1.646 1.646a.5.5 0 1 0 .708-.707L7.207 17.5l1.647-1.646a.5.5 0 0 0 0-.707M13.5 7.754c0 .38.282.693.648.743l.102.007l3.191-.001L13.5 4.559z");
}

</style>
