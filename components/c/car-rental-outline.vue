<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q459j5ble"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:car-rental-outline" /></template>
<style>
.q459j5ble {
  fill: currentColor;
  d: path("M8.385 6.885q-1.039 0-1.77-.731q-.73-.731-.73-1.77q0-1.038.73-1.768q.731-.731 1.77-.731q.892 0 1.561.572q.67.572.904 1.428h7.266v1h-1v2h-1v-2H10.85q-.234.856-.904 1.428t-1.561.572m1.058-1.442q.442-.441.442-1.058q0-.618-.442-1.059q-.441-.442-1.058-.442q-.618 0-1.059.442q-.441.441-.441 1.058q0 .618.441 1.06q.441.44 1.059.44t1.058-.44m-.288 11.25q.23-.23.23-.54t-.23-.54t-.54-.23t-.539.23t-.23.54q0 .31.23.54t.54.229t.539-.23m6.769 0q.23-.23.23-.54q0-.309-.23-.538t-.54-.23t-.539.23t-.23.539t.23.54t.54.229t.539-.23M6 14.408l1.496-4.3q.067-.216.24-.335q.172-.12.387-.12h7.754q.215 0 .388.12q.172.12.239.335l1.496 4.3V20.2q0 .196-.129.325t-.325.129h-.092q-.196 0-.325-.129T17 20.2v-1.546H7V20.2q0 .196-.129.325t-.325.129h-.092q-.196 0-.325-.129T6 20.2zm1.304-.754h9.392l-1.046-3h-7.3zm-.304 1v3zm0 3h10v-3H7z");
}

</style>
