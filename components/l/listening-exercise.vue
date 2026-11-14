<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hw07hbguo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:listening-exercise" /></template>
<style>
.hw07hbguo {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M3.75 13.643V12q0-3.417 2.416-5.834T12 3.75t5.834 2.416Q20.25 8.583 20.25 12v1.507q1.5.622 1.5 2.743v1.5q0 1.243-.879 2.121q-.878.879-2.121.879t-2.121-.879q-.879-.878-.879-2.121v-1.5q0-3 3-3V12q0-2.796-1.977-4.773T12 5.25T7.227 7.227T5.25 12v1.25q3 0 3 3v1.5q0 1.243-.879 2.121q-.878.879-2.121.879t-2.121-.879q-.879-.878-.879-2.121v-1.5q0-1.243.879-2.121q.29-.291.621-.486");
}

</style>
