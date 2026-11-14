<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mmydgab7b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:beam-lift" /></template>
<style>
.mmydgab7b {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M12.5 1.75h-1Q9 1.75 9 4.25q0 1.036.732 1.768q.642.642 1.518.721V7.5q0 .074.014.146q.015.073.043.141t.069.13q.041.061.094.113q.052.053.113.094t.13.069t.141.043t.146.014q1.75 0 1.75 1.75T12 11.75T10.25 10q0-.074-.014-.146q-.015-.073-.043-.141t-.069-.13t-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043T9.5 9.25t-.146.014q-.073.015-.141.043t-.13.069t-.113.094q-.053.052-.094.113t-.069.13t-.043.141T8.75 10q0 1.793.989 2.597L4.356 14.75H4q-2.25 0-2.25 2.25v2q0 2.25 2.25 2.25h16q2.25 0 2.25-2.25v-2q0-2.25-2.25-2.25h-.356l-5.383-2.153q.989-.804.989-2.597q0-2.85-2.5-3.201v-.06q.876-.079 1.518-.721Q15 5.286 15 4.25t-.732-1.768T12.5 1.75M12 13.308l3.606 1.442H8.394z");
}

</style>
