<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rn-6iub8b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:feed-24-filled" /></template>
<style>
.rn-6iub8b {
  fill: currentColor;
  d: path("M15 21a1.986 1.986 0 0 0 1.934-1.597l.48-2.403h2.836A1.75 1.75 0 0 0 22 15.25V9.261A2.26 2.26 0 0 0 19.75 7v-.004H14.5V5.25A2.25 2.25 0 0 0 12.25 3h-8A2.25 2.25 0 0 0 2 5.25v12.5A3.25 3.25 0 0 0 5.25 21zm2.522-12.182l-2.059 10.291a.486.486 0 0 1-.963-.095V8.496h3.11a2 2 0 0 0-.088.322M5.778 8.5a.75.75 0 1 1 0-1.5a.75.75 0 0 1 0 1.5m-.747 7.25a.75.75 0 0 1 .75-.75h5a.75.75 0 1 1 0 1.5h-5a.75.75 0 0 1-.75-.75m.75-4.75h5a.75.75 0 1 1 0 1.5h-5a.75.75 0 0 1 0-1.5");
}

</style>
