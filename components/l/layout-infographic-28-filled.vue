<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":28};
const content = `<path class="l9o-yzrbw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:layout-infographic-28-filled" /></template>
<style>
.l9o-yzrbw {
  fill: currentColor;
  d: path("M21.25 3A3.75 3.75 0 0 1 25 6.75v14.5A3.75 3.75 0 0 1 21.25 25H6.75A3.75 3.75 0 0 1 3 21.25V6.75A3.75 3.75 0 0 1 6.75 3zM10.5 13a4 4 0 1 0 0 8a4 4 0 0 0 0-8m6.25 1a.75.75 0 0 0-.75.75v5.5a.75.75 0 0 0 1.5 0v-5.5a.75.75 0 0 0-.75-.75m3-2a.75.75 0 0 0-.75.75v7.5a.75.75 0 0 0 1.5 0v-7.5a.75.75 0 0 0-.75-.75m-9.25 2.5a2.5 2.5 0 1 1 0 5a2.5 2.5 0 0 1 0-5m-2.75-7a.75.75 0 0 0 0 1.5h12.5a.75.75 0 0 0 0-1.5z");
}

</style>
