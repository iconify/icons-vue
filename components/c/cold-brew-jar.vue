<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l83-q6aws"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:cold-brew-jar" /></template>
<style>
.l83-q6aws {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M15.5 1.75h-7Q6.25 1.75 6.25 4q0 1.061.5 1.621v.892q-2.5 1.228-2.5 3.987V19q0 3.25 3.25 3.25h9q3.25 0 3.25-3.25v-8.5q0-2.759-2.5-3.987v-.892q.5-.56.5-1.621q0-2.25-2.25-2.25m2.75 16H5.75V10.5q0-1.992 2.029-2.804q.104-.041.191-.112q.088-.07.151-.164q.063-.093.096-.2T8.25 7v-.757q.121.007.25.007h.75v7.25q0 2.75 2.75 2.75t2.75-2.75V6.25h.75q.129 0 .25-.007V7q0 .112.033.22q.033.107.096.2t.151.164q.087.071.191.112q2.029.812 2.029 2.804zm-12.49 1.5h12.48q-.12 1.5-1.74 1.5h-9q-1.62 0-1.74-1.5m4.99-13h2.5v7.25q0 1.25-1.25 1.25t-1.25-1.25z");
}

</style>
