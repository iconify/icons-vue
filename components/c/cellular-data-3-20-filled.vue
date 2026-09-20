<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="psp7y4b2g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:cellular-data-3-20-filled" /></template>
<style>
.psp7y4b2g {
  fill: currentColor;
  d: path("M4.75 12a.75.75 0 0 1 .742.64l.008.11v2.496a.75.75 0 0 1-1.492.11L4 15.246V12.75a.75.75 0 0 1 .75-.75m3-2a.75.75 0 0 1 .742.64l.008.11v4.496a.75.75 0 0 1-1.492.11L7 15.246V10.75a.75.75 0 0 1 .75-.75m3-2a.75.75 0 0 1 .742.64l.008.11v6.5a.75.75 0 0 1-1.492.11L10 15.25v-6.5a.75.75 0 0 1 .75-.75");
}

</style>
