<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":28};
const content = `<path class="uqil9acgq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:clipboard-chat-empty-28-filled" /></template>
<style>
.uqil9acgq {
  fill: currentColor;
  d: path("M16 2a2.5 2.5 0 0 1 2.45 2h1.8A2.75 2.75 0 0 1 23 6.75v3.769A9 9 0 0 0 9.913 21.948l-.84 2.8A1.75 1.75 0 0 0 9.17 26H7.75A2.75 2.75 0 0 1 5 23.25V6.75A2.75 2.75 0 0 1 7.75 4h1.8A2.5 2.5 0 0 1 12 2zm-4 1.5a1 1 0 1 0 0 2h4a1 1 0 1 0 0-2zm6 6.5a8 8 0 1 1-3.852 15.012l-3.182.957a.75.75 0 0 1-.935-.935l.955-3.184A8 8 0 0 1 18 10");
}

</style>
