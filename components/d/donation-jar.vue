<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rsb0wm5dw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:donation-jar" /></template>
<style>
.rsb0wm5dw {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M17.25 1.75H6.75q-2.5 0-2.5 2.5q0 1.036.732 1.768q.251.25.537.415l-.715 1.788q-.054.135-.054.279V19q0 2.75 2.75 2.75h9q2.75 0 2.75-2.75V8.5q0-.144-.054-.279l-.715-1.788q.286-.165.537-.415q.732-.732.732-1.768q0-2.5-2.5-2.5m-11 6.894l.758-1.894h9.984l.758 1.894V19q0 1.25-1.25 1.25h-9q-1.25 0-1.25-1.25zM14 11.25h-4q-2.25 0-2.25 2.25q0 .951.402 1.5q-.402.549-.402 1.5q0 2.25 2.25 2.25h4q.932 0 1.591-.659t.659-1.591q0-.869-.572-1.5q.572-.631.572-1.5q0-.932-.659-1.591T14 11.25");
}

</style>
