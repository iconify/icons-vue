<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c7wkocc1c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:loading-arc" /></template>
<style>
.c7wkocc1c {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M17.125 3.123q3.677 2.123 4.776 6.224t-1.024 7.778t-6.224 4.776t-7.778-1.024t-4.776-6.224t1.024-7.778q.037-.064.086-.12t.107-.1q.059-.045.125-.078q.067-.032.138-.051q.071-.02.145-.024q.074-.005.147.004t.143.034t.134.06q.064.037.12.086t.1.107q.045.059.078.125q.032.067.051.138q.02.071.024.145q.005.074-.004.147t-.034.143q-.024.07-.06.134q-1.813 3.139-.875 6.64t4.077 5.313t6.64.874t5.313-4.077q1.812-3.138.874-6.639t-4.077-5.313q-.129-.075-.22-.193t-.129-.263q-.039-.144-.02-.292q.02-.148.094-.277q.037-.064.086-.12t.107-.1q.059-.045.125-.078q.067-.032.138-.051q.071-.02.145-.024q.074-.005.147.004t.143.034t.134.06");
}

</style>
