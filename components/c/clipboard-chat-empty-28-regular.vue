<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":28};
const content = `<path class="zm6f9ac7a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:clipboard-chat-empty-28-regular" /></template>
<style>
.zm6f9ac7a {
  fill: currentColor;
  d: path("M16 2a2.5 2.5 0 0 1 2.45 2h1.8A2.75 2.75 0 0 1 23 6.75v3.768a9 9 0 0 0-1.5-.809V6.75c0-.69-.56-1.25-1.25-1.25h-1.958A2.5 2.5 0 0 1 16 7h-4a2.5 2.5 0 0 1-2.292-1.5H7.75c-.69 0-1.25.56-1.25 1.25v16.5c0 .69.56 1.25 1.25 1.25h1.397l-.074.247A1.75 1.75 0 0 0 9.17 26H7.75A2.75 2.75 0 0 1 5 23.25V6.75A2.75 2.75 0 0 1 7.75 4h1.8A2.5 2.5 0 0 1 12 2zm-4 1.5a1 1 0 1 0 0 2h4a1 1 0 1 0 0-2zm6 6.5a8 8 0 1 1-3.852 15.012l-3.182.957a.75.75 0 0 1-.935-.935l.955-3.184A8 8 0 0 1 18 10m0 1.5a6.5 6.5 0 0 0-5.56 9.867c.11.182.138.402.077.606l-.648 2.157l2.157-.648a.75.75 0 0 1 .606.079A6.5 6.5 0 1 0 18 11.5");
}

</style>
