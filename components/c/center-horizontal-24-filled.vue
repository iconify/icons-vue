<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ebaj1u_hk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:center-horizontal-24-filled" /></template>
<style>
.ebaj1u_hk {
  fill: currentColor;
  d: path("M3.75 3a.75.75 0 0 1 .75.75v16.5a.75.75 0 0 1-1.5 0V3.75A.75.75 0 0 1 3.75 3m16.5 0a.75.75 0 0 1 .75.75v16.5a.75.75 0 0 1-1.5 0V3.75a.75.75 0 0 1 .75-.75m-10 2A2.25 2.25 0 0 0 8 7.25v9.5A2.25 2.25 0 0 0 10.25 19h3.5A2.25 2.25 0 0 0 16 16.75v-9.5A2.25 2.25 0 0 0 13.75 5z");
}

</style>
