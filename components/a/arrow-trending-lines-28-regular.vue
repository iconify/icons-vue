<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":28};
const content = `<path class="cqxe1laxm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:arrow-trending-lines-28-regular" /></template>
<style>
.cqxe1laxm {
  fill: currentColor;
  d: path("M4.75 20a.75.75 0 0 1 .75.75v3.5a.75.75 0 0 1-1.5 0v-3.5a.75.75 0 0 1 .75-.75m6-5a.75.75 0 0 1 .75.75v8.5a.75.75 0 0 1-1.5 0v-8.5a.75.75 0 0 1 .75-.75m6 2a.75.75 0 0 1 .75.75v6.5a.75.75 0 0 1-1.5 0v-6.5a.75.75 0 0 1 .75-.75m6-5a.75.75 0 0 1 .75.75v11.5a.75.75 0 0 1-1.5 0v-11.5a.75.75 0 0 1 .75-.75m1.502-9a.75.75 0 0 1 .75.75v4.5a.75.75 0 0 1-1.5 0V5.56l-6.97 6.97a.75.75 0 0 1-1.06 0L12.25 9.31l-6.97 6.97a.75.75 0 0 1-1.061-1.06l7.502-7.5l.056-.052a.75.75 0 0 1 1.004.052l3.22 3.22l6.44-6.44h-2.69a.75.75 0 1 1 0-1.5z");
}

</style>
