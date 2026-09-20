<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e92r2shwm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:mail-lock-outline-sharp" /></template>
<style>
.e92r2shwm {
  fill: currentColor;
  d: path("M3 19V5h18v4.225h-1v-2.34l-8 5.23l-8-5.23v10.5q0 .269.173.442t.443.173h11v1zm9-8l7.692-5H4.308zm-8 7V6zm13.616 1v-4.77h1v-1.114q0-.787.549-1.336t1.335-.55t1.336.55t.549 1.336v1.115h1V19zm1.769-4.77h2.23v-1.114q0-.464-.325-.79T20.5 12t-.79.326t-.326.79z");
}

</style>
