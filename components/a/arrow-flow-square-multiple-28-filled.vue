<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":28};
const content = `<path class="wguky4bxw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:arrow-flow-square-multiple-28-filled" /></template>
<style>
.wguky4bxw {
  fill: currentColor;
  d: path("M22.007 7.077a3.75 3.75 0 0 1 2.992 3.673v8a6.25 6.25 0 0 1-6.25 6.25h-8a3.75 3.75 0 0 1-3.675-3h10.183a4.75 4.75 0 0 0 4.75-4.75zM17.25 3A3.75 3.75 0 0 1 21 6.75v10.5A3.75 3.75 0 0 1 17.25 21H6.75A3.75 3.75 0 0 1 3 17.25v-5.357c.239.067.49.107.75.107a2.75 2.75 0 0 0 2.644-2h.356a4.25 4.25 0 0 1 3.4 1.7a5.75 5.75 0 0 0 4.6 2.3h1.69l-2.22 2.22a.75.75 0 1 0 1.06 1.06l3.5-3.5a.75.75 0 0 0 0-1.06l-3.5-3.5a.75.75 0 1 0-1.06 1.06l2.22 2.22h-1.69a4.25 4.25 0 0 1-3.4-1.7a5.75 5.75 0 0 0-4.6-2.3h-.356a2.75 2.75 0 0 0-3.391-1.895A3.75 3.75 0 0 1 6.75 3zM3.75 8a1.25 1.25 0 1 1 0 2.5a1.25 1.25 0 0 1 0-2.5");
}

</style>
