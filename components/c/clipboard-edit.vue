<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s2-6xh60j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:clipboard-edit" /></template>
<style>
.s2-6xh60j {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M6.5 4.25h1.257q.122-2 2.243-2h.75q-1.243 0-2.121.879q-.879.878-.879 2.121q0 3 3 3h2.5q3 0 3-3q0-1.243-.879-2.121q-.878-.879-2.121-.879H14q.932 0 1.591.659q.569.569.647 1.341H17.5q2.75 0 2.75 2.75v12q0 2.75-2.75 2.75h-11q-2.75 0-2.75-2.75V7q0-2.75 2.75-2.75m4.25-.5q-.621 0-1.061.439q-.439.44-.439 1.061q0 1.5 1.5 1.5h2.5q1.5 0 1.5-1.5q0-.621-.439-1.061q-.44-.439-1.061-.439zm4.608 6.892q-1.237-1.237-2.474 0L9.316 14.21q-.482.481-.615 1.149l-.088.439q-.142.709.369 1.22t1.22.369l.439-.088q.668-.133 1.149-.615l3.568-3.568q1.237-1.237 0-2.474");
}

</style>
