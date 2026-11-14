<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="isiv3f2da"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:dental-cost" /></template>
<style>
.isiv3f2da {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("m14.289 3.593l3.875 3.576q1.086 1.002 1.086 2.48v9.226q0 3.375-3.375 3.375h-7.75q-3.375 0-3.375-3.375V9.649q0-1.478 1.086-2.48l3.875-3.576q2.289-2.112 4.578 0M8.25 13.75q0 1.246.634 2.943q.301.806.381 1.204q.006.03.014.059l.5 1.75q.039.137.126.25q.087.114.209.187q.063.038.133.063t.143.036t.146.007q.074-.003.146-.021t.138-.05q.067-.031.126-.075q.06-.044.109-.099q.05-.055.088-.118L12 18.458l.857 1.428q.073.122.187.209q.113.087.25.126q.071.02.145.026q.073.007.147-.002q.073-.008.143-.031q.071-.023.135-.058t.121-.084q.056-.048.102-.106t.08-.123t.054-.137l.5-1.75q.008-.029.014-.059q.08-.398.381-1.204q.634-1.697.634-2.943q0-1.901-1.352-2.577q-1.076-.538-2.398.003q-1.322-.541-2.398-.003q-1.352.676-1.352 2.577");
}

</style>
