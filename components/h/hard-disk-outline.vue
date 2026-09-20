<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k6mimtbdd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:hard-disk-outline" /></template>
<style>
.k6mimtbdd {
  fill: currentColor;
  d: path("M6.616 21q-.691 0-1.153-.462T5 19.385V4.615q0-.69.463-1.152T6.616 3h10.788q.69 0 1.153.463t.462 1.153v14.769q0 .69-.462 1.153T17.404 21zm0-1h10.788q.269 0 .442-.173t.173-.442V4.615q0-.269-.173-.442T17.404 4H6.616q-.27 0-.443.173T6 4.616v14.769q0 .269.173.442t.443.173m1.769-2.384h7.25v-1h-7.25zM12 14q1.592 0 2.7-1.108t1.108-2.7t-1.108-2.7T12 6.385T9.3 7.492t-1.108 2.7t1.108 2.7T12 14m0-1.711q-.867 0-1.472-.615q-.605-.614-.605-1.482t.605-1.482T12 8.096q.887 0 1.501.605t.615 1.491t-.615 1.492t-1.501.605m.02-2.097");
}

</style>
