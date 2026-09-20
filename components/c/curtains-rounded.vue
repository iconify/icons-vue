<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g8vec4blz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:curtains-rounded" /></template>
<style>
.g8vec4blz {
  fill: currentColor;
  d: path("M5 19V5.616q0-.672.472-1.144T6.616 4h10.769q.67 0 1.143.472q.472.472.472 1.144V19h1.5q.214 0 .357.143T21 19.5t-.143.357T20.5 20h-17q-.213 0-.357-.143T3 19.5t.143-.357T3.5 19zm2.11-7q1.988.856 3.067 2.883T11.45 19h1.1q.194-2.09 1.273-4.117T16.891 12q-2.008-.856-3.087-2.883T12.53 5h-1.08q-.194 2.09-1.273 4.117T7.11 12");
}

</style>
