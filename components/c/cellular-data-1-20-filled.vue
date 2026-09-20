<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ifl44_78e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:cellular-data-1-20-filled" /></template>
<style>
.ifl44_78e {
  fill: currentColor;
  d: path("M4.75 12a.75.75 0 0 1 .742.64l.008.11v2.5a.75.75 0 0 1-1.492.11L4 15.25v-2.5a.75.75 0 0 1 .75-.75m3-2a.75.75 0 0 1 .742.64l.008.11v4.5a.75.75 0 0 1-1.492.11L7 15.25v-4.5a.75.75 0 0 1 .75-.75m3-2a.75.75 0 0 1 .742.64l.008.11v6.5a.75.75 0 0 1-1.492.11L10 15.25v-6.5a.75.75 0 0 1 .75-.75m3-2a.75.75 0 0 1 .742.64l.008.11v8.499a.75.75 0 0 1-1.492.11L13 15.25v-8.5a.75.75 0 0 1 .75-.75m3-2a.74.74 0 0 1 .74.626l.01.11l-.014 10.515a.743.743 0 0 1-1.477.124l-.009-.11l.014-10.515A.743.743 0 0 1 16.75 4");
}

</style>
