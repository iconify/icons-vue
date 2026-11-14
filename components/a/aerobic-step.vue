<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e440z7prx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:aerobic-step" /></template>
<style>
.e440z7prx {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("m2.815 8.446l.538-1.21q.66-1.485 2.284-1.485h12.726q1.624 0 2.284 1.484l.538 1.212q.518 1.165-.176 2.234q-.388.597-.957.861q.198.506.198 1.209v3q0 2.5-2.5 2.5h-1.5q-2.5 0-2.5-2.5v-3q0-.564.127-1h-3.754q.127.436.127 1v3q0 2.5-2.5 2.5h-1.5q-2.5 0-2.5-2.5v-3q0-.703.198-1.209q-.569-.264-.957-.861q-.694-1.069-.176-2.234");
}

</style>
