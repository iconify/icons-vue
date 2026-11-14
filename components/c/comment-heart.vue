<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t8-scpoey"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:comment-heart" /></template>
<style>
.t8-scpoey {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M7.384 20.313q3.993 2.426 8.36.573q4.527-1.922 5.465-6.75T18.67 5.83q-3.478-3.477-8.306-2.539t-6.75 5.465q-1.853 4.367.573 8.36l-.908 3.178q-.059.206 0 .412q.02.071.054.137q.034.065.08.123t.102.106t.121.084q.064.035.135.058q.07.023.143.031q.074.009.147.002q.074-.006.145-.026zm4.248-3.659Q7.25 14.189 7.25 11q0-3.25 3-3.25q1.014 0 1.75.622q.736-.622 1.75-.622q3 0 3 3.25q0 3.189-4.382 5.654q-.085.047-.178.072t-.19.024t-.19-.024q-.094-.025-.178-.072");
}

</style>
