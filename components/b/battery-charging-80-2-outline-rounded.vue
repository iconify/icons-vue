<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n--lxcbif"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:battery-charging-80-2-outline-rounded" /></template>
<style>
.n--lxcbif {
  fill: currentColor;
  d: path("M3.308 16.5q-.348 0-.578-.23t-.23-.578V8.308q0-.348.23-.578t.578-.23h11.238q.214 0 .357.143q.143.144.143.357t-.143.357t-.357.143H12.5v7h1.556q.213 0 .357.143t.143.357t-.143.357t-.357.143zm14.663-3.712h-2.19q-.248 0-.367-.207t.024-.42l2.581-4.063q.067-.092.153-.108q.086-.015.159.016t.134.103t.031.177l-.467 2.925h2.19q.248 0 .366.208t-.024.42l-2.58 4.063q-.068.092-.153.108q-.086.015-.159-.016t-.135-.103t-.03-.177z");
}

</style>
